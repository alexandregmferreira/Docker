# 🐳02 - Rodando uma imagem docker nginx 

#### 01- Primeiros vamos verificar se tem algum container rodando
<ul>
	<li> docker ps </li>
	<li> <img src="img/01.png"> </li>
</ul>

#### 02- Neste exemplo vamos usar uma imagem do docker hub, nginx 
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
