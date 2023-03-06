# Dokumentation

Dette er min egen dokumentation af Java Webstack. vi skal lave et intranet og vil bruge denne dokumentation til 
bedre at kunne huske hva vi lavede.

## Start af et nyt webprojekt

1. Opret nyt projekt i IntelliJ
2. Vælg JavaEE projektskabelon
3. Java + Maven
4. Servlet dependecies

![img/webstart.png](img/webstart.png)

## Arkitektur

Vi anvender en slags MVC-pattern.

![img/mvc.png](img/mvc.png)

- M(odel) - Entiteter og hjælpe- metoder og klasser. Business-logic
- V(iew) - JSP og frontend ( css, bootstrap mm)
- C(ontrol) - Servlets

Husk! Ingen kommunikation mellem Model og View. Gå altid igennem controlleren.

```shell
git init
git add .
git commit -m "initial commit"
```