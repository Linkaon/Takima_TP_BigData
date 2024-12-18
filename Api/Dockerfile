# Utiliser OpenJDK 17 avec JDK
FROM openjdk:17-jdk-slim

# Définir le répertoire de travail
WORKDIR /app

# Créer le répertoire pour le package API
RUN mkdir -p /app/Api

# Copier le code source dans le répertoire approprié
COPY ./Main.java /app/Api/Main.java

# Afficher le contenu du répertoire pour déboguer
RUN ls -la /app/Api

# Compiler l'application Java
RUN javac /app/Api/Main.java

# Vérifier le contenu après compilation
RUN ls -la /app/Api

# Exécuter la classe principale avec le package
CMD ["java", "Api.Main"]
