--- Epic Online Services ---

Link to EOS: https://onlineservices.epicgames.com/en-US/services

1. Primero has de entrar en el enlace, logearte con tu cuenta de Epic Games e ir a Dev Portal en la esquina superior derecha.

2. Una vez hecho esto, debes crear tu organización. El nombre de la organización no tiene ninguna importancia dentro del proyecto. 

3. Una vez creada la organización toca crear un producto en el que vas a poder conectar tu proyecto de modo online. Esta opción figura en el menú de la izquiera de la pantalla.

4. Tras la creación del producto, accedemos dentro del mismo y entramos a la opción Settings. Dentro de esta opción acudiremos a la parte de Client, en la cual crearemos la política de nuestros clientes en la parte inferior de toda la ventana con el nombre de "Client Policies".
* Enlace a la documentación de los tipos de cliente y políticas: https://dev.epicgames.com/docs/dev-portal/client-credentials

5. Dentro de la misma opción iremos a la pestaña de cliente donde tendremos acceso a la creación de clientes en funcion a las necesidades del proyecto.

6. Tras crear el cliente, nos habrá generado varios codigos para poder hacer uso de ellos más adelante en el plugin del motor.

7. Una vez finalizado esto, iremos a la parte de Account Services. Haciendo click en Create Application. Por el momento solo configuraremos Permissions y Linked Clients.

8. En Permissions activaremos Online Presence y Friends.

9. En Linked Clients aplicaremos el cliente creado dentro del paso 5.

10. Una vez todo configurado solo queda ir al apartado principal de nuestro producto, este figura con el nombre del producto en el menú de la izquierda, habitualmente suele esta en negrita.
Haciendo Click en la opción SDK & Release Notes. (Sigue en EIK INSTALL)

---- EIK INSTALL ----

Link to Plugin Documentation: https://eik.betide.studio/
Link to Download Plugin: https://github.com/betidestudio/EOSIntegrationKit

1. En primer lugar, con ayuda de la documentación completaremos el paso 10 de Epic Online Services, seleccionando el SDK que necesitemos para la creación del proyecto.

2. Tras ello, descargaremos el Plugin en el ‫Github que figura en la parte superior del apartado

3. Una vez descargado el Plugin seguiremos los pasos concretos indicados en la documentación superior, este paso puede ser distinto en función de si instalas para Android, Windows etc..

4. Compila el proyecto.

5. Tras abrir el proyecto, accede al Project Settings, donde a un lado tendrás un nuevo menú que se llama EOS Integration Kit. En estas opciones debes marcar en primer lugar Automatically Setup EIK (Esto pedirá reiniciar el motor)

6. Adicionalmente, dentro del archivo DefaultEngine.ini debes añadir las líneas que figuran en la documentación del pluggin, en el apartado de Manual Configuration (Es importante añadirlas, la instalación automática no añade algunas veces estas lineas y da problemas de conexión entre Cliente y Servidor después)

7. Dentro del menú de Project Settings, en el apartad del Pluggin, hay una opción que se llama Artifact Settings, debemos crear un nuevo elemento ahí dentro y tendremos que darle una configuración concreta. En el producto que hemos creado en Epic Online System nos darán las credenciales para rellenar estos campos. 
* En caso de Android más abajo en el mismo menú se puede crear otro artefacto, es necesario rellenar los dos.
Enlace a la documentación del paso 7: https://eik.betide.studio/getting-started/configuration


