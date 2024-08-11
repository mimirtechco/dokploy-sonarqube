# dokploy-sonarqube

Sonarqube Docker Compose for Dokploy

**Attention**: this compose file uses an external Postgresql database. Please create one before on your dokploy and set credentials on your environment.

```
SONAR_JDBC_URL: jdbc:postgresql://db:5432/sonar
SONAR_JDBC_USERNAME: sonar
SONAR_JDBC_PASSWORD: sonar
```