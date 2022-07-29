# Creación de un Bot.
**Objetivo:** Crear un BOT, que pueda conversar con una persona.   

![](/imagenes/bot.jpg)

**Requisitos**
- Cuenta de Azure con una suscripción activa
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs. 

**Pasos**  
Ingresamos a la página de https://www.qnamaker.ai/ e iniciamos sesión.  
Damos clic en el apartado de Create a knowledge base.  
Damos clic a Create a QnA service, esto nos mandara a Azure.  
![Imagen 1](/imagenes/Imagen1.png)

En Azure llenamos los siguientes datos:

**En Detalles del proyecto**  
Suscripción: La suscripción que utilizamos anteriormente.  
Grupo de recursos: Utilizamos el grupo de recursos que creamos hace unos momentos.  
Nombre: Colocamos el que queramos.  
Plan de tarifa: Seleccionamos el que queramos.

**En Detalles de Azure Search para datos**  
Ubicación de Azure search: Podemos escoger cualquiera, pero si no queremos que haya mucha latencia escogemos uno cercano a donde vivimos.  
Plan de tarifa de Azure search: Seleccionamos el que queramos.

Para terminar, damos clic en el botón de revisar y crear, y luego en crear.  
![](/imagenes/Imagen2.png)

Nos regresamos a QNA Maker y llenamos lo que nos piden.  
![](/imagenes/Imagen3.png)

En chit-chat podemos seleccionar como queremos que sea la actitud de nuestro bot, al terminar, le damos en crear tu KB.  
![](/imagenes/Imagen4.png)

Damos clic en add QnA pair.  
Podemos poner una pregunta y una respuesta o muchas en esta parte.  
Cuando queramos poner una nueva pregunta y respuesta solo le volvemos a poner en add QnA pair.
![](/imagenes/Imagen5.png)

Al terminar de colocar las preguntas y respuestas, damos clic en save and train y damos clic en test, para poder probar lo que acabamos de hacer.  
![](/imagenes/Imagen6.png)

Una vez que acabemos de probar el funcionamiento del bot,  damos clic en el botón de publish. Ahí nos mostrara un código en HTTP para poder usar el bot donde queramos o podemos subirlo en Azure. 