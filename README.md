# Desafíos Java
Consultas a desafios@xeven.com.ar

¡Recuerden que estos son desafíos, no cursos!

Se responderán dudas puntuales sobre la consigna o cómo encarar un problema.

No se responderán dudas técnicas que puedan resolver ustedes mismos con una búsqueda en StackOverflow o un video en YouTube.

### ¡No olviden registrarse! [https://goo.gl/forms/ziYeCU3iQ9PjF2PG2](https://goo.gl/forms/ziYeCU3iQ9PjF2PG2)

## Primer desafío
La idea es crear una aplicación web simple que corra en Heroku.

Esto nos va a permitir ir agregando nuevas funcionalidades en el sistema.

Ejemplo funcionando: [https://xevendes01.herokuapp.com/](https://xevendes01.herokuapp.com/)

Vamos a utilizar varias tecnologías en este primer desafío: JavaEE, Git, Heroku, HTML, CSS.

En los próximos releases / desafíos vamos a agregar muchas más, incluyendo Spring, Hibernate, AJAX y otras que ya me fueron pidiendo. :-)

### Instrucciones

1. Crear un proyecto en un IDE de su elección (sugiero intellij), desde cero o clonando [este repositorio](https://github.com/pabloxeven/desafiosJava).
2. Agregar un Web Application Server (sugiero GlassFish) y Maven (v3).
3. Agregar un index.jsp y correr el proyecto en local.
4. Crear una cuenta en Heroku.com, conectar con Github y automatizar el deployment con el branch Master de su repo o usar el Git de Heroku.
5. Subir el contenido a su cuenta en heroku.
6. Compartir la URL de heroku generada, con el proyecto funcionando.
7. C'est tout!

 ### Tips adicionales
 
 * Sobre el punto 1, sugiero usar IntelliJ básicamente porque es un IDE ampliamente usado en el mercado. Si quieren usar Netbeans o Eclipse pueden hacerlo. Yo sólo daré soporte (muy limitado) sobre intellij.
 
 * Sobre el punto 2 lo mismo, pueden elegir cualquier WAS, lo importante es que puedan correrlo en local y comprobar que funciona todo antes de avanzar. ¡Consulten tutoriales sobre instalación y configuración del que usen!
 
 * Sobre el punto 4, este es difícil, lo sé. La parte de crear cuenta y conectar con git lo sacan en seguida. Automatizar el deployment tiene 2 pasos importantes que explico brevemente: Una vez creada la app se van a "Deploy" y abajo conectan con Github a su repo. Activen los automatic deploys a Master. Luego, [instalan heroku en sus máquinas](https://devcenter.heroku.com), inician sesión con el CLI y [crean la app](https://devcenter.heroku.com/articles/getting-started-with-java#deploy-the-app). Recuerden que el CLI lo usan desde cualquier terminal (macOS / Linux) o consola (Windows).
 ___
 
 __XEVEN Informática__
 
 Mayo 2017
