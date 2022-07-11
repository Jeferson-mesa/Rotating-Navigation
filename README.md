# Rotating-Navigation
Exercise Rotating Navigation

Instrucciones de Implementación

Feliz Navidad y bienvenido al reto 3, para cumplirlo deberán seguir lo siguiente:

1. Ver el video de explicación de reto.

2. Tienen los siguientes recursos: Entregamos el HTML con las imágenes y títulos a usar(assets), css básico y js con la estructura que deben seguir*
   
   * Acá les damos una estructura y una guía de cómo deben hacerlo sientanse libres de cambiar el código en donde necesiten para llegar al resultado final.

3. Deberán completar el css y el js para que el reto funcione.

Resultado: El reto debe ser igual al que visualizan en el video, sean detallistas

¡HINTS!

CSS

Completar el CSS con las clases faltantes:

nav 

content


JS

con un evento click y una función arrow crear el efecto para abrir y cerrar la navegación

open.addEventListener('click', () => container.xxxxxxxxx )

close.addEventListener('click', () => container.xxxxxxxxxxxxxx)


¿Como resolvi el ejercicio?
Inicialmente dividi la pantalla de mi computador en 2 para ver la pagina finalizada y el proyecto base que se nos dio.
Pude observar que la imagen principal era mucho mas grande que como deberia quedar, asi que empeze por ahi y logre ajustarla con un "max-width: 100%;"
Seguido de eso no sabia por donde empezar para hacer el menu en el lado izquierdo, por ende busque en youtube y encontre en el css la clase "show-nav", la aplique al container y efectivamente se desplego el menu
Teniendo el menu desplegado me puse a acomodar los iconos para que quedaran igual a la pagina, se le quito el list-style, individualmente los movi para que quedaran con 15px de diferencia a lado izquierdo y asi se generara ese efecto de "cascada". tambien le agregue un transition para que cada vez que se recargue la pagina se genere ese efecto de traslado hacia el centro de la pagina
Lo unico que faltaba era hacer el boton "open" and "close" funcionara respecto al menu, asi que, me meti en archivo JS y ya estaban nombradas las constates, procedi a llamarlas y a crearles un evento. Para el "Open" era tan facil como decirle que añadiera la clase 'show-nav' en el container y para el "Close" removerla
