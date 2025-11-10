# 🐳03 - Rodando uma imagem spring boot

### O que é Spring Boot?
#### Spring Boot é um framework Java de código aberto que simplifica e acelera o desenvolvimento de aplicações web e microsserviços baseadas no Spring Framework
#### Fonte: https://spring.io/guides/gs/spring-boot-docker




#### 01- Primeiros vamos realizar o download dos arquivos necessários para realizar o build

<ul>
        <li> Neste caso vou usar o Maven  </li>
	<li> a href="https://start.spring.io/#!type=maven-project&language=java&packaging=jar&jvmVersion=11&groupId=com.example&artifactId=spring-boot-docker&name=spring-boot-docker&description=Demo%20project%20for%20Spring%20Boot&packageName=com.example.spring-boot-docker&dependencies=web">Projeto </a</li>
        <li> <img src="img/01.png"> </li>
</ul>

<ul>
        <li> docker run -d --name nginx-teste -p 80:80 nginx
                <ul>
                        <li>Usamos o parametro -d para rodar o container em segundo plano </li>
                        <li>Usamos o parametro --name para dar um nome ao container </li>
                        <li>Usamos o parametro -p para expor uma porta </li>
                        <li>Ao final do comando inserimos a imagem que queremos rodar </li>
                </ul>
        </li>
        <li> <img src="img/02.png"> </li>
</ul>

#### 03- Verificaremos agora se o container esta rodando

<ul>
        <li> docker ps </li>
        <img src="img/03.png">
</ul>

#### 04- Agora que sabemos que o container está rodando, vamos fazer o teste via navegador

<ul>
        <li> http://localhost:8080 </li>
        <li> <img src="img/04.png" </li>
</ul>

