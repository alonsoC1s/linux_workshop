# Taller de Linux - Sesión 00 - Guión

## Introducción

> Amigos, amigas, itamitas y no tan itamitas... Ustedes son esclavos, y venimos a emanciparlos.  

% Propongo el cambio al párrafo anterior: Amigos, amigas, itamitas y no tan itamitas... Por años nos han dicho que nuestra libertad es lo más valioso que tenemos, y hoy venimos a ayudarte a defender la libertad de tu vida digital. 

"¿Esclavos de qué?" De seguro se preguntan.  

Pues... Esclavos a grandes corporativos, cuyo deseo es atraparte consumiendo eternamente sus productos en particular: que si ustedes compran una Mac, a fuerzas tengan que comprar un iPhone, un iPad, suscribirse a iCloud, y gastar miles de i-pesos en renovar sus equipos (que, por cierto, cada vez van en mal en peor), mínimo, cada dos años.  

% Comentario: Muuuuy bueno, pero muuuuuuy colorido. Quizás "demasiado" colorido

También son esclavos a miles de entidades públicas y privadas, hambrientas por sus deliciosos, y muy rentables, datos. Ansiosas de saber cómo te llamas, dónde vives, cuántos años tienes, cuál es tu estado civil, qué relación tienes con tu abuela, qué raza es tu perro, a qué hora vas al baño, por qué te gusta comer jugo de manzana todos los sábados a las 20:25 horas... ¿Para qué quieren saber todo eso? Shhhh... No preguntes, querido consumidor. Mejor mira la foto que subió tu tía Martha (la que se acaba de divorciar hace 2 semanas) con sus hijos, Íker Ignacio y Daniel Antonio, en Tepetongo hace 7 horas con 6 minutos. Y mientras estás con eso, ¿ya viste este titular de El Financiero que cuenta cómo la volvió a cagar el Peje...? Eso mirrey, léelo, enójate, reacciona, compártelo, escribe un post de mil palabras sobre porque te indigna tanto. Permíteme, mientras haces eso, deja le muestro a tu tío chairo unos 7 videos del Chapucero, y luego tu post... Me gusta ver cómo se pelean.  

Bueno, en resumen, todos ustedes son esclavos al software cerrado. A aquellos programas que, si bien podemos usar, no tenemos ni idea de cómo están hechos. ¿Quién dice que Tik-tok no está grabando tus conversaciones privadas y mandándolas a una policía secreta China? Y el navegador que usas... ¿Por qué chingados ocupa tanta RAM? ¿No será porque andará ahí minando Bitcoin con tu poder de procesamiento? Estaría muy chido checar si esto es cierto o no, pero... No podemos. Los programas que tienes instalados en tu computadora (o teléfono, tablet, etc) ya están compilados... No sabemos como se hicieron. Imagina comprar una jugosa arrachera en un restaurant. Está a muy buen precio, término 3/4, le puedes ver la sangresita y el jugo. El olor... Ya se imaginarán, y te la sirven con una salsa de tomate y especias que sabe a poca... Pero, más tarde, terminas en el hospital porque, esa salsa, tenía extracto de camarón y tú tienes una muy fuerte alergia a los mariscos.

¿Por qué les doy todo este chorro mareador? Por que, el hablar de Linux, es hablar software libre y open source. Usar Linux, y programas que se apegan a su filosofía, significa poder checar el código de cada programa para ver que no haga fregaderas. Significa acceder a ese programa gratuitamente, por siempre, y poder modificarlo a mi gusto. O, en otras palabras, si hubieras pedido una arrachera libre y open-source, hubieras podido ver la receta del platillo y cada uno de los ingredientes de la salsa para poder decir, con completa confianza y libertad, "quíteme el camarón de la salsa, por favor".

## Historia
Ahora, para entender un poco más del software libre y open-source, necesitamos hablar un poquito de historia. Desde el auge de las computadoras hasta la década de los 60, el programar una compu significaba manipular físicamente las señales eléctricas de la maquína y que tenía que dedicar todos sus recursos a hacer una sola cosa. Imaginen que quisieran leer un libro pero, en vez de comprarlo en una librería, tuvieran que ir al bosque a talar unos árboles, secarlos, procesar la pulpa, ponerle cloro para hacerlo papel, cortar las hojas, y luego ir con un escriba y pedirle "me transcribes este libro, pofavo".  

Fue en los 60s cuando se solucionó este problema gracias a los primeros sistemas operativos: conjuntos de programas que se ocupaban de la interacción entre el humano y los circuitos de la computadora para no tener que andar manejado las señales electricas de una a una, o, siguiendo con nuestra analogía, para que, en vez de hacer todo ese rollo para sacar un libro desde 0, pudieras ir a la librería o biblioteca a comprarlo. Ya alguien más, que le sabe más al asunto, se encargó de imprimir y distribuir el libro.  

Así nacieron varios sistemas operativos. Uno fue MS-DOS, que eventualmente se volvió Windows. Pero, el que nos importa ahorita, es este otro: Unix. Unix fue desarrollado en Bell Labs (en ese entonces el lugar más fregón en cuanto a investigación y desarrollo de computación) por Ken Thompson y Dennis Ritchie (lo que Benito Juárez y Lázaro Cárdenas son a México, lo son Ken Thompson y Dennis Ritchie a la computación). Gracias a su éxito dentro de Bell Labs, AT&T (la empresa entonces dueña del laboratorio) la empezó a licenciar a varias empresas y organismos. En ese entonces, esa licencia incluía acceso al código fuente de Unix. Gracias a esto, mucha gente empezó a hacer sus variates de Unix. Una notable, por ejemplo, fue BSD (la Berkeley Software Distribution), de la UC Berkeley.  

Pero todo cambió cuando atacaron los políticos. EUA hizo reformas a sus leyes de derechos de autor en 1976 que causaron que se dejara de distribuir el código fuente del software. Esto significaba, por supuesto, que universidades como Berkeley estaban en pedos legales con el gigante de AT&T por usar el código de Bell Labs.  

% Comentario: Quizás demasiado énfasis en Stallman está de más. Además de que a pesar de sus contribuciones, es una basura de persona y acosador sexual y no queremos enaltecerle de más :)

Ahora entra en escena Richard Stallman. Este compa es un genio: es de los pocos estudiantes en la historia de Harvard en sacar buenas calificaciones en la clase Math 55. Esta clase es de las más difíciles de mates en Harvard: hagan de cuenta que se trata de chutarse todo Álgebra Superior, Mates Discretas, Cálculo 1, 2 y 3, Geo. Analítica y Álgebra Lineal en dos semestres. Este compa ve lo que está pasando y dijo "oigan, esto es como si mi tía Martha le hubiera pasado su receta de pay de manzana a la familia, y, a partir de ella, mi abuela sacó su pay de plátano, mi mamá su pastel de chocolate, el primo chino de mi tío del gabacho unas trufas de atole... Y, ahora, mi tía quiere demandar a todos los que hayan usado su receta y/o hayan hecho una variante de la misma con alguno de los ingredientes. ¡No se vale!¡Deberías poder compartir tus recetas con tu vecino si te da la gana...!  

¿Saben qué? Al chile, voy a hacer mi propia receta de Pay de manzanas sin usar ninguno de los ingredientes de la mugrosa tía Martha para que toda mi familia pueda hacer sus propios pays, y le voy a hacer una licencia para que los vecinos puedan también hacer sus propias recetas." Ahora remplazen "Martha" por AT&T, "pay de manzana" por "sistema operativo" y familiares por "todos ser humano habido y por haber en la tierra". El proyecto de Stallman era GNU (acrónimo para "GNU's Not Unix"); un conjunto de programas que sustituirían todos los de Unix para que no quede ni un rastro del código que hizo Bell Labs. El código fuente de estos programas sería de libre acceso y modificación, y completamente gratuitos, a tal punto que toda modificación de GNU también tendría que ser libre y open source.  

Para principios de los 90, el trabajo de GNU, que ya involucraba a un montón de colaboradores, ya casi estaba completo: habían reemplazado casi todas las apps de Unix... Excepto por una cosa: el kernel. Si un sistema operativo fuera una hamburguesa, GNU ya había reemplazado la carne, el jitmoate, la lechuga, la mostaza, mayonesa, catsup y pepinillos... Pero aún faltaba reemplazar el pan (el kernel), lo que hacía que la hamburguesa no se desparrame.  

Afortudanamente, Linus Torvalds, un estudiante de la Universidad de Helsinki estaba trabajando en su propio kernel. Le quería poner un nombre bien tonto, *Freax*, disque para no ser presumido... Pero un administrados de su uni le dijo que no friegue y le cambió el nombre a Linux. Los compas de GNU, al ver el kernel Linux, dijeron "prestas" y completaron su proyecto, bautizándolo oficialmente como "GNU/Linux" (o Linux, pa los cuates).

## Las distros

Gracias a esta apertura, un montonal de empresas, non-profits, entusiastes, universidades, o simples locos en sus casas empezaron a hacer sus versiones de Linux, con total y completa libertad, solo les agregaron ciertos componentes para hacerlos más complejos y los distribuyeron como sistemas operativos, listos para instalar, cada uno con su propio look & feel. A estos sistemas operativos basados en Linux se les conocen como "Distribuciones de Linux", o, simplemente, "Distros".  

Tenemos algunas distros que sirven para hacer funcionar como una compu de escritorio común y corriente, como Ubuntu, PopOS, Manjaro y Fedora. Otras son para servidores, como RHEL. Otras se especializan en ciberseguridad, como Kali Linux. Otras buscan parecerse a Mac OS como Manjaro Cutefish o a Windows como KDE Neon. Otras se instalan en computadoras muy débiles; hasta en tostadoras (de hecho, si un electrodoméstico se conecta a internet, lo más probable es que corra una distro de Linux).  

Puede ser que utilizen una Windows o Mac en su día a día... Pero Linux los rodea. Los servidores en donde corren sus apps y sitios web favoritos son Linux, como les dije, su tostadora es Linux. Y, como no mencionarlo, si tienen un teléfono Android están utilizando una distro de Linux.

## Conclusión

Esta libertad hace de Linux súper personalizable y, por lo tanto, el mejor entorno, no solo para programar, sino también para hacer casi cualquier cosa.  

Vean este timelapse, por ejemplo: en la derecha estoy escribiendo un ensayo para Seminario en Google Docs, y, en la derecha, el mismo texto con unas herramientas específicas de Linux (muestra el timelapse). Y, claro también me he dado la libertad de personalizar mi sistema Linux a mi gusto (muestra imágenes de mi Rice). Aparte, por favor, escuchen a mi computadora en este video (muestro video) y escuchenla ahora (muestro video). En ambos video estoy haciendo lo mismo, ver un video en Youtube. Y, para rematarla, esta transmisión la estamos haciendo con software 100% libre y open source en una computadora que corre Linux.  

>Por eso, más que enseñarles a utilizar e instalar Linux (que por supuesto que vamos a hacer), este taller sirve para que se den cuenta del poderío del software libre; de poder colaborar y crear programas chidos para el bien de todo el planeta con gente de todo el mundo, beneficiando a miles y puliendo su CV de forma que sea mil veces más atractiva para todo empleados.  

% Propongo editar el párrafo anterior a lo siguiente:
Si bien el objetivo de este curso es darles las herramientas para conocer íntimamente Linux y hacerlo su SO del día a día, esperamos darte mucho mucho más que eso. Queremos darte una probadita de cómo es entrar al mundo del software libre, queremos darte las herramientas para que te animes a exigir tu privacidad y libertad de usar _tu_ computadora como _a ti_ te plazca. Queremos que como nosotros, encuentres en la comunidad Open Source la oportunidad de colaborar y crear programas chidos para el bien de todo el planeta con gente de todo el mundo, beneficiando a miles y puliendo su CV de forma que sea mil veces más atractiva para todo empleador.  

Así que, consideren esto como una invitación. Una invitación a tomar la píldora roja. Una invitación a liberarse de la esclavitud que ya dije, de poder agarrar una compu vieja y hacer que corra como nueva. Una invitación a emanciparse con Linux y el software libre.  

Gracias.

% Comentario general: Me gusta el contenido, pero el tono se acerca al terreno de condescendiente y poco invitador. Por ejemplo "esclavos" se usa mucho y es una palabra muy fuerte
