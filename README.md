# Documentación Página web tributo WIB ¿Wich one is better? 
> ![image](https://user-images.githubusercontent.com/108433878/194413137-948ead25-6d19-4435-a0ce-8b8840643f23.png)

*Desarrollado por: Cristian Camilo Betancourt Rincon* 

Página realizada con HTML y Css utilizando el IDE Visual Studio Code.

*La temática de la página tributo es sobre suspensiones de bicicleta, su tecnología, diseño y funcionamiento. Para ello, se han integrado diferentes apartados gráficos que permiten ver su diseño. Por otra parte se hace un recorrido específico por cada suspensión explicando cuáles son sus tecnologías ofrecidas y por último, se hace una comparativa de precios entre diferentes gamas de cada suspension. Adicionalmente, se ha diseñado un foro en el cual las personas podrán interactuar sobre sus experiencias usando cada suspensión.*

### Extensiones utilizadas: 
* Live server
* Html format
* Html preview
* Htmls Snippets
* Html CSS Support.


## Estructura principal: 
```bash
	<head>
	      <meta charset="UTF-8">
	      <meta http-equiv="X-UA-Compatible" content="IE=edge">
	      <meta name="viewport" content="width=device-width, initial-scale=1.0">
	      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-iYQeCzEYFbKjA/T2uDLTpkwGzCiq6soy8tYaI1GyVh/UjpbCx/TYkiZhlZB6+fzT" crossorigin="anonymous">
	      <link rel="stylesheet" href="/Css/style.css">
	      <title>Wich One Is Better</title>
	      <link rel="icon" type="image/x-icon" href="/img/WIBlogo.png">
  	</head>
 ```
> ## *Nota*
> * Se define la etiqueta Lang = es para mejorar los servicios de automatización y para que se reconozca el lenguaje utilizado. 
> * Se integran las etiquetas de compatibilidad preestablecidas del navegador X UA compatible. 
> * Se adjunta el enlace a las librerías de Bootstrap utilizadas (bootstrap)
> * Le linkea el documento con la pagina de css que va a alterar directamente el contenido. <link reel= “stylesheet”>
> * Se genera el titulo que se va a mostrar en la pestaña con <title>
> * Se adjunta el icono que se muestra en la pestaña con <link reel =”icon” 


## Footer
```bash
                                                               
    <footer>
      <div class="info_footer">
        <div class="idioma"> <img src="/img/footer lenguaje.png" alt="" width="300px" height="" class="bandera"></div>
        <div class="img_desarrollador"> <img src="/img/footer marca.png" alt="" width="400px"></div>
        <div class="contacto">
          <a href="https://www.facebook.com/cbetancourtrincon1"><img src="/img/footer contacto.png" alt="" width="100px" height="80px"></a>
          <a href="https://github.com/CrisCaBeRi"><img src="/img/footer contacto 1.png" alt="" width="100px" height="80px"></a>
          <a href="https://api.whatsapp.com/send?phone=573123679015&text=Hola, ví tu página web y me interesan tus servicios de desarrollador."><img src="/img/footer contacto 2.png" alt="" width="100px" height="80px"></a>
        </div>
      </div>
    </footer>
 ```
> ![image](https://user-images.githubusercontent.com/108433878/194413691-5ec40d3c-9dc8-4c4b-85ac-4818ad7a221a.png)

> ## *Nota* 
> * Se crea la sección <footer> 
> * Se crea un div con la clase intro footer que va a contener diferentes imágenes distribuidas horizontalmente 
> * Dentro del div intro footer, se generan 3 div aparte que contienen diferentes imágenes, el último div contiene 3 imágenes con link de hipervínculo que conducen a Facebook, GitHub y WhatsApp, el ultimo abre el hipervínculo y muestra un mensaje preestablecido. 

## Links a librerías de Bootstrap 
```bash
<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js" integrity="sha384-oBqDVmMz9ATKxIep9tiCxS/Z9fNfEXiDAYTujMAeBAsjFuCZSmKbSSUnQlmh/jp3" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.min.js" integrity="sha384-7VPbUDkoPSGFnVtYi0QogXtr74QeVeeIs99Qfg5YCF+TidwNdjvaKZX19NZ/e6oz" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-u1OknCvxWvY5kfmNBILK2hRnQC3Pr17a+RTT6rIHI7NnikvbZlHgTPOOmMi466C8" crossorigin="anonymous"></script>
```
> ## *Nota* 
> * Se copian las rutas de la página de Bootstrap para los elementos preestablecidos que van a ser usados y se pegan en la parte final del documento por fuera de la etiqueta </html>

## Header 

```bash
<header>
  <div id="header">
    <div class="botones_inicio">
      <button class="btn1"> <a href="/principal.html"><div class = txt_btn1>Inicio</div> </a></button>
        <div class="dropdown">
          <button class = "btn2"><div class = txt_btn2>Suspensiones</div></button>
              <div class="dropdown-content">
                <div class=" desplegable_1"><a href="/suntour.html"><div class="txt_desplegable1">Suntour</div></a></div>
                <div class=" desplegable_2"><a href="/fox.html"><div class="txt_desplegable2">Fox</div></a></div>
                <div class=" desplegable_3"><a href="/rockshox.html"><div class="txt_desplegable3">Rock Shox</div></a></div>					
              </div>
          </div>
     <button class="btn3"> <a href="/foro.html"><div class = txt_btn3>Foro</div> </a></button>	
	</div>
	    <div class="imagen_logo"><img src="/img/WIBlogo.png" alt="" width="270px" ></div>			
  </div>
 </header>
```
> ![image](https://user-images.githubusercontent.com/108433878/194413806-5dd72956-11b6-45e8-9f57-b3efccd577fe.png)

> ## *Nota* 
> * Se crea la etiqueta header donde se alamacena el encabezado que consta de 3 botones y logo de la aplicación distribuidos de manera horizontal. 
> * Se crea una etiqueta div que contiene todos los botones correspondientes. 
> * Dentro de la etiqueta div s crean los botones btn1 y btn3 con los enlaces correspondientes. 
> * Para el botón 2 se crea un div “dropdown” que contiene un botón general y otro div con sub- botones en forma desplegable, todos ellos con un hipervínculo correspondiente. 
> * El ultimo div, contiene la imagen del logo. 

## Contenido de las páginas 

```bash
<section class=" carrusel"> 
	<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
		<div class="carousel-indicators">
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="3" aria-label="Slide 4"></button>
		</div>
		<div class="carousel-inner">
		  <div class="carousel-item active">
			<img src="/img/carrusel_principal.png" width="100%" height="1080px" class="d-block" alt="...">			
		  </div>
		  <div class="carousel-item">
			<img src="/img/carrusel suntour.png" width="100%" height="1080px" class="d-block " alt="...">
			
		  </div>
		  <div class="carousel-item">
				<img src="/img/carrusel fox.png" width="100%" height="1080px" class="d-block" alt="...">					
			</div>
			<div class="carousel-item">
				<img src="/img/carrusel rock shox.png" width="100%" height="1080px" class="d-block" alt="...">					
			</div>
		</div>
	  </div>	
</section>
```
> ![image](https://user-images.githubusercontent.com/108433878/194413935-130b111a-2247-4053-9428-1a36c99a1d5b.png)
> 
> ## *Nota* 
> * Se crea la sección carrusel que almacena el elemento extraído de la librería de Bootstrap (este elemento consiste en un carrusel de fotografías que se desplazan de izquierda a derecha)
> * Para cada elemento se crea un div aparte para que pueda ser modificado en posición.
> * Las etiquetas buton se crean para poder navegar entre las imágenes del carrusel. 
> * Las etiquetas de carrousel-inner y carrousel-item contienen las imágenes del carrusel con un ancho y alto establecido en 100% ancho y 1080 px de alto. 

```bash
<hr>
	<section class="especificacion">
		<h1>Según especificación <br> técnica </h1>
		<p>Comparativa de cada ítem <br> específico</p>
		
		<div class="imagenes_especificacion">
			<img src="/img/tecnologias.png" alt="" width="500px" class="sombra" >		
			<img src="/img/diseño.png" alt="" width="500px">
			<img src="/img/precios.png" alt="" width="500px">
		</div>
	</section>
<hr>
	<section class="video">
		<iframe width="80%" height="1000px" src="https://www.youtube.com/embed/sbajy7DzQcM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	</section>
```
> ![image](https://user-images.githubusercontent.com/108433878/194414075-9c7f26d5-0c64-4ec6-8a47-c50132ccf4ca.png)
> ## *Nota* 
> * La etiqueta hr se utiliza después de cualquier sección para dividir contenidos. 
> * se crea la sección especificación que contiene un titulo h1 y una etiqueta de párrafo con contenido de texto. 
> * Se crea la etiqueta de imagenes_especificacion para almacenar tres imágenes de forma horizontal
> * Por último, se crea la sección de video donde se utiliza la etiqueta <iframe con el enlace del video y el tamaño establecido. 

## Paginas Suntour, Fox y Rock Shox
Se utiliza la misma estructura de código presentado a continuación, las únicas diferencias varían en las imágenes utilizadas y los textos. 

```bash
<section class="carrusel"> 
	<div id="carouselExampleCaptions" class="carousel slide" data-bs-ride="false">
		<div class="carousel-indicators">
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
		  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>		  
		</div>
		<div class="carousel-inner">
		  <div class="carousel-item active">
			<img src="/img/ROCK 1.png" width="100%" height="1080px" class="d-block" alt="...">			
		  </div>
		  <div class="carousel-item">
			<img src="/img/ROCK 2.png" width="100%" height="1080px" class="d-block " alt="...">
			
		  </div>
		  <div class="carousel-item">
				<img src="/img/ROCK 3.png" width="100%" height="1080px" class="d-block" alt="...">					
			</div>	
		</div>
	</div>	
	<div class="textocarrusel">
		<div class="imagen_texto">
			<h1>32 SID ULTIMATE</h1>
			<img src="/img/logo rock shox.png" alt="" class="superiorrock">
		</div>
		<p>Embalado en un chasis rígido y ligero de 35 mm, y equipado con el amortiguador de rendimiento más ligero que jamás hayamos fabricado: Charger™ Race Day. Perfectamente equilibrada para saciar tu necesidad de velocidad XC.</p>
		<img src="/img/iconos_superiorROCK.png" alt="" class="iconosrock">
	</div>	

</section>
```
> ![image](https://user-images.githubusercontent.com/108433878/194414481-ac158327-a995-49b9-a3b3-45da16fc2203.png)
> ## *Nota* 
> * La sección de carrusel se utiliza de nuevo. En este caso se agrega una etiqueta div “textocarrusel” que contiene una imagen superior del logo de marca, un título y párrafo correspondiente y otra imagen al final. 

```bash
<section class="tecnologias_fox">
	<div class="textos_fox">
		<h1>Tecnología</h1>

		<h2>DEBONAIR</h2>
		<p>Cámara de aire desarrollada para una sensación suave como la mantequilla desde la parte superior, ahora optimizada para mantener una mayor altura de manejo y agregar más confianza en terreno técnico.</p>

		<h2>SAG GRADIENTS</h2>
		<p>Ajuste de recorrido para los cartuchos SAF con el fin de evidenciar qué recorrido tiene la suspensión en práctica.</p>

		<h2>MAXIMA PLUSH FLUID</h2>
		<p>Integracion del aceite Maxima Plush Fluid diseñado para proteger del mugre, la fricción y el movimiento del damper.  </p>		
			
		<h2>BOOST SYSTEM </h2>
		<p>Sistema de eje pasante con compatibilidad de 15m X 110 y 15 X 100 en ruedas 27.5 y 29”.</p>

		<h2>SKF SEALS </h2>
		<p>Integraciópn de retenes de la más alta calidad sin perder suavidad ni funcionalidad. </p>

		<h2>CHARGE RACE DAY DAMPER </h2>
		<p>Sistema de bloqueo para finales de Sprint o subidas no técnicas. </p>
	</div>

	<img src="/img/iconos_tecnologíaROCK.png" alt="imagen fox parte de abajo" height="2200px" >
</section>
```
> ![image](https://user-images.githubusercontent.com/108433878/194414557-6ed3b642-34f3-4927-8c43-187a66065d48.png)
> ## *Nota* 
> * Se crea la sección “tecnologías” que almacena una etiqueta div de textos; finalmente, se encuentra otra etiqueta img con una imagen correspondiente. 
 
```bash
<section class="precios">
	<div class="precio_desde_fox">

		<div class="texto_desde">
			<h1>Desde</h1>
			<h2>1.070,21€</h2>
			<img src="/img/bandera-colombia.jpg" alt="" width="65px">
			<h2>COP | 4.699.000</h2>
			<p>Modelos 2022<br>RockShox SID SL <br> Ultimate 29"</p>
		</div>

	</div>

	<img src="/img/flechas ROCK.png" alt="" class="imagen_precios" width="300px" height="200px">

	<div class="precio_hasta_suntour">
		<div class="texto_hasta">
			<h1>Hasta</h1>
			<h2>1.415,71€</h2>
			<img src="/img/bandera-colombia.jpg" alt="" width="65px">
			<h2>COP | 6.215.990</h2>
			<p>Modelos 2023 <br> Rockshox Sid Select <br>Charger Rl</p>
		</div>
	</div>
	<div class="precios_logo">
		<h1>Precios</h1>
		<img src="/img/Precio ROCK.png" alt="">
	</div>
</section>
```
> ![image](https://user-images.githubusercontent.com/108433878/194414695-56efbde8-8ade-4b9a-bf08-dc468c38137e.png)
> ## *Nota* 
> * Por último, se crea la sección precios que almacena 3 etiquetas div que alimentan contenido de texto párrafo e imágenes distribuidas en “precio desde” y “precio hasta”. 
> * Dentro de la sección, también se encuentran una imagen correspondiente que divide los dos divs iniciales.  




