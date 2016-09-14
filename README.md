# traduccion-formulario

Usando selectores, cambia los textos que aparecen por su traducción o equivalente a español

![english](http://i63.tinypic.com/2mwxic0.jpg)

Una serie de métodos nos permiten manipular los nodos, de forma que podemos buscarlos , modificarlos. (leer comentarios en HTML)

```HTML
<body>
    <div class="container">
      <form class="form-signin">
      <!--document.getElementById("form-signin-heading").innerHTML="Por favor inicia sesión"-->
        <h2 id="form-signin-heading">  
          Please sign in
        </h2>

        <label for="inputEmail" class="sr-only">
          Email   
        </label>
        <!--//document.getElementById("inputEmail").placeholder="Correo Electrónico"-->
        <input type="email" id="inputEmail" class="form-control" placeholder="Please enter your email" autofocus="">  

        <label for="inputPassword" class="sr-only">
          Password
        </label>
        <!--document.getElementById("inputPassword").placeholder="Contraseña"-->
        <input type="password" id="inputPassword" class="form-control" placeholder="Password" required="">
        
        <div class="checkbox">
          <label>
          <!--document.querySelector("span").innerHTML="Recordar datos"-->
            <input type="checkbox" value="remember-me">
            <span>Remember me<span>
          </label>
        </div>
        <!--document.querySelector("button").innerHTML="Iniciar Sesión"-->
        <button class="btn btn-lg btn-primary btn-block submit-btn" type="submit">Sign in</button>
      </form>
    </div>
  </body>
```

METODOS USADOS

  - getElementById()
    Devuelve el elemento cuyo atributo id sea igual al que se le pasa en el parámetro. Se aplica normalmente a document. 
    Como el valor de id debe ser único en cada elemento, sólo puede devolver uno.
    
  - querySelector()
    Acepta como parametro un selector que identifa al elemento a seleccionar.
    
Luego de realizar los cambios nuestro formulario se vera asi en español:

![español](http://i68.tinypic.com/11j81ky.jpg )

