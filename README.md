# Poc with Liquibase

## Liquibase's working

### ![Insert](image/Insert.png)

### includeAll

Liquibase va rechercher dans le dossier tous les changeLogs à exécuter puis les exécuter un à un. 
Toutefois, cette méthode est à utiliser avec beaucoup de prudence car Liquibase va exécuter les fichiers changeLogs par ordre alphabétique. 
Au sein de l’équipe, il convient donc de définir au préalable une convention de nommage des fichiers changeLogs afin d’éviter d’avoir des fichiers chargé dans un ordre erratique…

### include
Need to specify all files one by one.

### preConditions

## Sources
- https://blog.soat.fr/2015/10/liquibase-et-le-versioning-de-base-de-donnees/
- https://www.baeldung.com/liquibase-refactor-schema-of-java-app
- https://docs.spring.io/spring-boot/docs/current/reference/html/appendix-application-properties.html#data-migration-properties
- http://www.liquibase.org
- http://www.liquibase.org/bestpractices
- http://www.liquibase.org/documentation/changes/index.html
- http://www.liquibase.org/documentation/databasechangelog.html
- https://www.liquibase.org/documentation/column.html