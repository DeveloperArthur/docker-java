Acesse o Terminal, navegue até a pasta do Dockerfile e builde a imagem Docker:

````
docker build --tag=minha-api-java:latest .
````

Suba o Container:
````
docker run -d -p 8080:8080 minha-api-java
````
