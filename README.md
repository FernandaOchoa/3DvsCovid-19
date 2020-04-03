# Impresiones 3D vs Covid-19
Investigación personal sobre las Impresiones 3D para el área médica.

**[Link a la Actualización al 30 de Marzo](https://github.com/FernandaOchoa/3DvsCovid-19/blob/master/Actualizaci%C3%B3n-30-03-2020.md)**

Hola, quiero comenzar con que esto es meramente personal, sin ánimos de lucrar y con la genuina intención de ayudar.

Ahora con lo del COVID-19, está increíble que todos nos sumemos desde nuestras áreas para generar un aporte, de pronto todos nos sentimos útiles y neta hay propuestas que van más allá del prototipo y logran ser implementados en estos momentos de contingencia.

Me ha llamado mucho la atención la cantidad impresionante de innovaciones tecnológicas en el área biomédica, si bien es cierto que en Italia, España, y USA, están haciendo implementaciones de emergencia y probando nuevos prototipos, es preciso recalcar, que la etapa en la que ellos se encuentran es por mucho más complicada que la que enfrentamos en este momento nosotros. Es decir, algunas implementaciones que se hacen allá son por el nivel de la contingencia y la relación costo/beneficio es clave. 

Les recomiendo si están en un proyecto similar lean el libro de Cardiothorasic Critical Care, hablan de soportes respiratorios no invasivos. Me leí gran parte para poder entender el problema, además de otras fuentes.

### El problema

Sin embargo para México la historia debe ser distinta, por que hemos reaccionado a tiempo y se están realizando diversos esfuerzos conjuntos, todos en pro de ayudar. Precisamente por tener "más tiempo" no podemos intentar implementar lo que en países con un nivel de contingencia mayor, sin hacer modificaciones o mejorías a lo que ya se propuso, es decir ir por el modelo de utilidad, en lugar de replicar.

Por ello una de las principales tecnologías que han sido más populares es la de la impresión 3D, sin embargo como mencione antes, debemos hacer modificaciones a lo que ya existe, por que aún cuando el material pueda ser de grado médico ([FDA](https://www.fda.gov/)) es importante recalcar que la [técnica de impresión varía por marca y por material (pág.20)](https://repository.usta.edu.co/bitstream/handle/11634/474/elaboracion%20y%20caracterizacion%20componentes%20plasticos%20porosos%20mediante%20impresion%203d%20para%20aplicaciones%20de%20regeneracion%20osea.pdf?sequence=1&isAllowed=y), dejando como resultado la famosa **Porosidad**, Recordemos que el virus COVID-19 tiene un tamaño [80-160nM](https://www.ejmo.org/pdf/2019%20Novel%20Coronavirus%20COVID19%20Outbreak%20A%20Review%20of%20the%20Current%20Literature-12220.pdf). 

A lo que quiero llegar, que es la porosidad de las impresiones existe independiente del material (Un Ing. en Plásticos y Polímeros reafirma todo lo que menciono en este documento (MC. Yareli). Bueno, con esto en mente hay otro factor preocupante y es que con la sudoración, el contacto con la piel, el oxígeno inclusive, se pueden generar las condiciones ideales para que aparezcan bacterias y hongos, que básicamente es lo último que queremos en una urgencia médica, es por eso que el material debe ser de grado FDA, sino ni existiría el material. [Aquí hay algo al respecto](https://cults3d.com/es/blog/articles/10-cosas-que-debe-saber-impresion-3d-seguridad-alimentaria) aunque a mí me lo comentaron Ing. Mecatrónicos y Biomédicos (Victor y Rosalinda).

Ya, que todo esto es suficiente para entender que si seguimos imprimiendo como locos vamos a tener un desperdicio de material y habríamos ayudado a propagar el virus, o no.. quién sabe, aunque existe la probabilidad y si no es ese serían bacterias o yo no sé.

### El proyecto

Y bueno mientras veía como todos intentan hacer un respirador artificial, cosa que es de lo más complejo y me parece que llevaría más tiempo, caretas de acetato y las plataformas de crowdfounding para los pequeños negocios, me encontré con un prototipo que también ya existe, sin embargo la pieza es en 3D, lo que me llevo a pensar que eventualmente se desecharía y que a mi parecer en México no hay tanto equipamento para los médicos y no habrá el suficiente. Por lo que me dí a la tarea de investigar y ver que se podía hacer respecto a lo que encontré en internet.

Me gustó mucho el prototipo de Italia de la empresa [IsInnova](https://www.isinnova.it/easy-covid19-eng/) con la máscara de Snorkel, se me hizo una genialidad, por que de alguna manera podían mantener aislado al paciente y no era tan invasivo (A mí parecer).

![Mascara de Snorkel Modficada](https://www.isinnova.it/wp-content/uploads/2020/03/DSC3147-scaled.jpg)

Sin embargo la pieza es impresa en 3D, al estar en contacto con la toma de gases médicos (Pared de Oxígeno y Vacío) está el proceso de regulación para no contaminar la zona a donde van a parar lo que el paciente exhala. Pero piensen en la porosidad del material... podría infectarse o contraer una complicación. Recuerden que no soy médico o del área así que no esperen explicaciones tan técnicas y mis ejemplos son algo burdos. Si bien tooooda la investigación del lado médico se ha validado con médicos internistas, neumólogos y enfermeras. (Aron, su maestro, el maestro de omar y mi súper enfermera Karla Fernanda).

![Toma de Gases Médicos](http://www.diarioformosa.net/notix/multimedia/imagenes/fotos/2019-08-01/402570.jpg_crop.jpg)

Y modelos para imprimir hay muchos, sin embargo insisto el problema es que no son de grado médico, así que escogí un modelo y así como en los hackatones pareciera increíble que a todos se les ocurre la misma idea sin si quiera interactuar así mero me paso a mí.

![IMG_20200324_174524_6](https://user-images.githubusercontent.com/9124597/77814440-be564c80-7076-11ea-89a9-267509ea16d3.jpg)

Sólo que yo no sé diseñar y bueno, lo dibuje, tome como base lo de italia y agregué el conector que dice HME, ese pedacito es lo que se me ocurrió de una hace un tiempo que podía funcionar por qué el filtro ayudaba, sin embargo no consideré como "target" a los pacientes, sino a los médicos y cualquier persona vulnerable. 

El modelo que como mencioné no es el objetivo, sino que hay que hacerle modificaciones al mismo para evitar lo que mencionaba anteriormente. (Además de que en el modelado me ayudaron por que tampoco se bien de esto, gracias Mike).

![IMG-20200325-WA0007](https://user-images.githubusercontent.com/9124597/77814485-2147e380-7077-11ea-9396-abb0049f3e2b.jpg)

Pues después de que me llegó la máscara tuve que buscar en dónde se podía imprimir la pieza, fue un problema por que en Dolores Hidalgo, no hay una sola impresora 3D. Así que hay que traerlas de León, pero no todos los servicios son económicos por que al día de hoy 27/03/2020 hay 22 casos confirmados y 67 en investigación. Lo que dificulta la logística para distribución fuera de y en especial a Dolores Hidalgo. Se hizo una búsqueda simple en facebook y hubo buena respuesta, Omar nos regalo la impresión en cuanto vio que era para esta causa <3. 

Literal tuve que pedir un uber de su casa (por que obvio todo esta cerrado) al depa de mi novio (Gracias Paco) quién tenía un viaje a San Miguel de Allende y de pasada dejo las piezas. Lo comentó por que el virus llega a todas las ciudades y aún siendo impresión 3D es muy complicado acceder a esas tecnologías en ocasiones. Karla me ayudo a conseguir filtros especiales para el prototipo, Mike me conecto con los proveedores en León y Paco me trajo todo, los filtros unos cubrebocas y las piezas impresas). Posterior a eso tuvimos que desinfectar paquetes y todo por que uno no sabe.

![IMG_20200326_124635_7](https://user-images.githubusercontent.com/9124597/77814663-da5aed80-7078-11ea-8990-0230da617708.jpg)

### La posible solución

Y pues bueno, una vez que comprobamos que todo encajaba perfectamente, comenzó el tratamiento y es la fase en la que me encuentro ahorita, se le esta dando un recubrimiento especial a las piezas para que posteriormente se desinfecten por UV.

Con esto podríamos decir que mitigamos el problema de la porosidad. Es importante ya que no queremos que el virus penetre en el material por el nivel de exposición al virus y de permanencia del mismo en las superficies. Por recomendación de un QFB con master y actualmente en su phD (Betsie) menciono las credenciales por que neta fui con expertos de cada área, se llegó a la conclusión de que una capa extra de desinfección constante era necesaria, me recomendo varios químicos para ello.

![Recubrimiento](https://media.giphy.com/media/h1tvO9POLaoSX4fLZi/giphy.gif)

Por lo que además del recubrimiento anti-porosidad y la esterilización uv, se aplica una capa especial antimicótica (sin hongos), bactericida y hace que el virus se muera en un periodo considerablemente más rápido.

Aunque todo este esfuerzo es en vano si no se demuestra lo que les he mencionado, por lo que además hay que hacer pruebas bacteriológicas y sorpresivamente me anunciaron previamente que la impresión 3D no las pasa, así que mi investigación en recubrimientos para la impresión es cuando se torna relevante, al menos para mí. El estudio que se realiza es un estudio completo de superficies + hongos. Se van a requerir 2 de mínimo, uno de el prototipo tal cual, con recubrimiento antiporosidad y el segundo con el prototipo completo, a 10 horas de uso (una estimación de una jornada de un médico en la 1era línea). Cada uno tiene un costo de $1200.00 mxn y como ven se van a requerir 2.

Buscando que esto sea efectivo, permitiendonos, poder sumar todos los esfuerzos para que la impresión 3D pueda participar sin inconvenientes en las distintas soluciones y aportes. 

### Cómo ayudar 

Si bien esto es financiado desde mi quincena, he recibido aportaciones de material como la impresión, me donaron uno de los filtros. 
No quisiera que esto se vea como oportunismo o humo en el que si las cosas no resultan los decepcione o desperdicien el dinero. Por que literalmente lo hago con o sin aprobaciones jaja. 

No se en realidad como funciona asi que pueden ayudar con eso por ejemplo. 
Ah y tampoco se de licenciamientos, así que puedo decirles que si esto funciona publicare los resultados, planos, químicos y modelos de todo lo que se necesita para replicarlo, siempre y cuando sea sin fines de lucro.

Por lo único que me gustaría fondear esto es por que con un estudio bacteriologico positivo, es más sencillo bajar el recurso y que dolores tenga su propia impresora 3D para los médicos de aquí. Aunque tambien estamos haciendo moldes y probando materiales pero eso es caro y solo puedo una cosa a la vez.

### Agradecimientos

Toda mi investigación no sería posible sin ustedes. Agradezco su confianza y su apoyo <3

Familia
* Mamá y sus préstamos jaja
* Mi hermano que es mi mano derecha.
* Mis hermanas 
* Selene
* Paco <3

Medicina
* Aaron Rico
* Karla Fernanda

Mecatrónica
* Victor Hugo
* Miguel Gómez

Biomédica
* Rosalinda Guevara

Impresión 3D
* El profe de Mike

Plásticos y Polímeros
* MC Yareli

QFB
* Betsie Martínez
* Cristian Saldaña
