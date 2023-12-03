# Auditoria de Gestión

En este documento se encuentran las respuestas a las preguntas planteadas en la infrografía, aquellas que se usaron como una checklist.

## Requerimientos

**¿Se encuentran claramente definidos y redactados?**

Los requerimientos fueron definidos concretamente desde la primera entrega, pero con el avance del proyecto estos evolucionaron para llegar a ser lo que tenemos en la tercera entrega. Básicamente la evolución se debió a la viabilidad de la interfaz de la aplicación, ya que, había requerimientos propuestos que no podían testearse fácilmente y que esto requería conceptos más allá de lo que hemos visto. 

**¿Son consistentes entre sí?**

Definitivamente lo son, pues todos tienen en consideración lo que dicen los demás, evitando que se repitan funcionalidades entre la redacción de cada uno. Se podría decir que en la tercera entrega se aprecia este punto, pues es en donde pudimos describir claramente lo que necesitaríamos al ya poder apreciar una interfaz en forma de nuestra aplicación. 

**¿Los requerimientos están bajo un control de versiones?**

No lo están todas, las primeras versiones de estos requerimientos sí se encuentran documentados como una versión, pero, esta documentación de versiones fue abandonada por parte del equipo. Principalmente por la forma tan informal en la que lo realizamos en la primera entrega. 

**¿Cada requerimiento tiene un propietario designado?**

Desde el principio de la app se asignaron los propietarios, pues cada integrante fue quien propuso un requerimiento funcional y uno no funcional. Así pues, se acordó que cada uno trabajaría en mejorar sus requerimientos propuestos, teniendo en cuenta que estos podrían cambiar de liderazgo o que estos podrían llegar a ser eliminados o remplazados. 

**¿Existe un equilibrio adecuado entre la complejidad y la granularidad de los requerimientos?**

Así es, pues en la forma de redactarlos que hubo en la segunda entrega se específica sobre lo que estos implica, específicamente en las historias de usuario, en las que se habla sobre cómo debería ser cada uno de ellos y lo que implica que estos estén en un estado de aprobatorio o en estado de terminado. 

**¿Los requerimientos están prioritizados según su importancia y valor para el cliente?**

Sí están, principalmente en la tercera entrega, donde nos guiamos de la interfaz que teníamos ya lista y en donde nos pudimos dar cuenta en lo que implicaba cada uno de ellos.

También, durante las pruebas que se realizaron de estos requerimientos, se pudo notar cómo reaccionaron los usuarios y se pudo concluir que aquellos requerimientos propuestos coincidían a lo que se buscaba cuando se empezó a hablar de la idea de la app en la primera entrega. 

**¿Existe un proceso formal de aprobación para los requerimientos?**

No existe, es mas bien como algo que se acuerda informalmente entre los miembros del equipo, dando pie a que muchas veces estos requerimientos no estén completamente definidos y que se tengan que hacer modificaciones en las tres entregas que hubieron con el motivo de no caer en banalidades. 

**¿Se mantiene un historial de cambios para cada requerimiento?**

Desde el principio esto fue importante en el equipo y, la principal forma de hacerlo, es mediante el repositorio creado en la primera entrega, pues los artefactos subidos no han sido modificados desde la que se subieron. 

**¿Se mantiene actualizado el estado de cada requerimiento (pendiente, en progreso, completado)?**

Se mantienen actualizados mediante un tablero en el repositorio del equipo, pero se consideran en general y no como uno por uno. Esto es algo que sabemos que no debería ser así, pero como ya tenemos una idea principal de lo que son, pues consideramos que debería ser algo que ya se ve por el equipo y no hace falta explicitarlo dentro del repositorio. 

**¿Existe un proceso establecido para revertir a versiones anteriores si es necesario?**

Sí, los archivos de requerimientos previos propuestos se encuentran en el repositorio, y al estar trabajando mediante gitkraken, estos pueden ser recuperados en cualquiera de las ramas existente en el github. 

**¿Se ha llevado a cabo una revisión de los requerimientos con las personas correspondientes?**

Las revisiones fueron llevadas a cabo primero con el equipo, acordando que la forma de planteralas había sido la correcta en cada entrega. Posteriormente, estas fueron revisadas por el profesor Luis Basto quien nos señaló correcciones de ellas y la forma en la que deberíamos mejorarlas o remplazarlas en algunos casos. También tomamos en cuenta las indicaciones dadas por el profesor Cambranes acerca de la forma en la que nos costaría comprobar ciertos requerimiento que se habían propuestos previamente. 

**¿Los requerimientos son técnicamente viables y coherentes con la arquitectura y tecnologías seleccionadas?**

Al ser propuestos para una aplicación móvil, los requerimientos sí son viables pues pueden ser observables de muchas maneras dentro de la app. Así pues las tecnologías con las que contamos para realizarlo sí nos ayudaron, aunado a esto, podemos decir que son coherentes pues no provocaron que cambiáramos de proyecto en ningún momento de el avance del mismo.

## UI design

**¿La interfaz de usuario mantiene una consistencia visual en términos de colores, tipografía y elementos gráficos en todas las pantallas?**

Al momento del cambio de colores en la entrega dos, se decidió que esos colores tendrían que estar presentes en toda la interfaz, dando paso a una interfaz limpia y que no distrae al usuario con colores vibrantes al momento de contactar formalmente a las autoridades correspondientes. 

**¿La navegación entre pantallas es intuitiva y fácil de entender?**

Conforme a las pruebas realizadas, nos podemos dar cuenta que sí son intuitivas, más al momento de realizar una llamada de emergencia, pues se reportó un 100% de éxito los testing del UI design. 

**¿La interfaz se adapta de manera efectiva a diferentes tamaños de pantalla y dispositivos?**

No, por el momento sólo nos centramos en la interfaz propuesta para un iphone 14, con las medidas que nos daba la aplicación Figma y centrándonos en las reglas que se proponen para la creación de aplicaciones en el entorno de apple.

**¿Los botones y elementos interactivos son lo suficientemente grandes y táctiles para una fácil interacción?**

Sí lo son, son botones grandes con las medidas dadas por las reglas de apple y que son intuitivos para cualquier caso de emergencia, incluyendo una pequeña descripción para cada caso de emergencia, buscando incluir a las personas sordas que leen y las que no. 

**¿La interfaz es accesible para usuarios con discapacidad auditiva?**

Definitivamente lo es, pues es lo que buscábamos desde el principio de la app, algo creado específicamente para las personas con discapacidad auditiva y que sea completamente accesible para ellos. De hecho, muchas veces nos sentíamos confundidos sobre cómo se deberían plantear, para que no fueran tan invasores al momento de entrar a la app y para que fueran simples y accesibles para las personas sordas analfabetas. 

**¿Los iconos utilizados son fácilmente comprensibles y se ajustan al estilo visual de la aplicación?**

Así es, tuvimos una junta con nuestro profesor en la que nos indicó sobre aquellos iconos que no eran completamente entendibles y que tenían que ser modificados, por esto fueron modificados par al a tercera entrega. Al momento buscábamos que fueran iconos que no fueran tan simples, pues debíamos tener en cuenta que las situaciones de emergencia fueran entendibles y que identificaran por cuál de ellas estaban pasando. 

**¿Se mantiene un historial entre las versiones de la interfaz?**

La primera versión de la app se encuentra en el mismo archivo de figma pero en una pestaña correspondiente, así como en el repositorio del equipo. La segunda versión está igualmente en el figma pero como la principal pestaña de esta. Asimismo, la documentación está en el repositorio en donde se habla sobre la creación de cada icono y la actualización de los mismos. 

**¿Se mantiene actualizado el estado de cada pantalla (pendiente, en progreso, completado)?**

Dentro de el tablero del equipo se mantiene como una tarea general de cada entrega, pero entre el equipo nos comunicamos para saber cómo está el avance de cada pantalla designada con un historia de usuario. 

**¿Los archivos de diseño (por ejemplo, archivos PSD, Sketch, Figma) están bajo control de versiones?**

Sí, pues constantemente se están documentando y revisando grupalmente para saber si lo que se está realizando está correcto, o rechazando ideas que provocarían que la app no se pareciera a lo que se planteó en la primera entrega del proyecto. 

**¿Se implementan medidas para prevenir cambios no autorizados en los archivos de diseño?**

No, ya que todo el equipo tiene acceso al archivo de diseño, aunque debemos decir que sí tenemos designadas a personas específicas al UI design. Fue un acuerdo que hubo entre el equipo y que ha seguido así en todo el semestre, dando pie a que el diseño nunca haya sido modificado de manera errónea. 

**¿La herramienta de diseño se encuentra actualizada a su última versión?**

La herramienta en cuestión es el figma, se encuentra en su última versión pues nos encontramos usando la versión web que siempre está actualizada. 

**¿Existe documentación que describa la configuración del entorno de diseño?**

Sí, ambas documentaciones se encuentran el el repositorio. Desde el primer boceto de la interfaz se planteó que era de suma importancia que esta documentación existiera y que serviría para que en futuras entregas entendiéramos el propósito que le habíamos dado a cada pantalla; igualmente serviría para que le profesor observara aquello que habíamos realizado y captara la idea detrás de cada botón y pantalla.
