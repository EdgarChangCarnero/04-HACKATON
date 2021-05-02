¿Qué es ESLint?

Es una herramienta que pertenece al grupo Linting y existen para todos los lenguajes de programación, en nuestro caso, para JavaScript, la cual es unos de los lenguajes que más se utiliza con esta herramienta y es probablemente la más usando en todo el mundo para prevenir errores, en nuestro caso JavaScript. Al utilizar esta herramienta nos ayuda a identificar errores de código, por lo tanto, a mejorar nuestro código y sino no instalamos está herramienta no podríamos darnos cuenta.

Son dos pasos muy importantes que se tiene que instalar para trabajar con ESLint:

La primera es que, para instalar ESLint se requiere instalar Nodes, ahora, al crear un proyecto se recomienda crear la carpeta de trabajo con el nombre de la carpeta sin mayúsculas y sin espacios. Al trabajar el proyecto con la carpeta creada, puedes abrirlo con un editor de texto, en este caso yo lo abriré con Visual Studio Code. para trabajar con Nodes tienes que abrir la terminal de Visual Studio Code (ctrol + ñ), en la terminal escribes “npm init -y”, este “y” es para que todos los valores me lo ponga por defecto y el Visual Studio Code crea la carpeta package.json. Lo siguiente es instalar ESLint de forma global, para eso se pone en la terminal “npm install -g eslint”, cuando instalamos de forma global, lo estamos instalando en nuestro equipo no en el proyecto, es por eso que se tendrá que ejecutar solo una vez. Ahora vamos a iniciar nuestro proyecto de ESLint. En la terminal de Visual Studio Code ingresamos el comando “eslint –init”,  la terminal nos mostrará una serie de preguntas, en lo personal marcaré la última que es la más completa (to check syntax, find problems, and enforcé code style), lo siguiente que nos preguntas es que tipo de módulos vamos a usar en nuestro proyecto, yo seleccionaré “Ninguno de estos”, después nos pregunta por los Framework vamos a utilizar nuestro proyecto (React y Vue.js), yo seleccionaré “Ninguno de estos”, también nos pregunta si vamos a usar TypeScript (y/n), yo pondré no (n), también nos pregunta donde se va a ejecutar nuestro proyecto, en un navegador (Browser) o en Node, yo solo lo ejecutaré en el navegador y por ultimo nos dice, como nos gustaría definir el estilo de nuestro proyectos, se recomienda utilizar la primer opción, “Use a popular style guide”, la que más se utiliza y la que más se usa en el mundo es la “Airbnb”, pero hay otras alternativas como “Standart” y “Google”. Ahora seleccionamos “Airbnb” y la terminal nos pregunta donde queremos la configuración de ESLint (JavaScript, YAML Y JSON), lo normal es seleccionar JSON y nos pregunta si queremos instalar los estilos atreves de “npm”, le digo que sí. Una vez termine ya tendremos instalado ESLint para usarlo en Visual Studio Code. La herramienta ESLint la encuentras en el siguiente link https://eslint.org/

El segundo paso es Visual Studio Code necesita comunicarse con ESLint. Entonces nos vamos a la Extención de Visual Stedio Code (Ctrol + Shift +X) y escribimos ESLint, podemos verificar que tiene 14,193,212 de descargas e instalamos.

Libros donde trabajan con ESLint


1.	Learning React: Modern Patterns for Developing React Apps
https://books.google.com.pe/books?id=tDjrDwAAQBAJ&pg=PA224&dq=ESLint&hl=es-419&sa=X&ved=2ahUKEwjp0vjll6vwAhW9qJUCHZOeAWcQ6AEwAHoECAMQAg#v=onepage&q=ESLint&f=false

2.	Learning Node.js for .NET Developers
https://books.google.com.pe/books?id=u_1vDQAAQBAJ&pg=PA83&dq=ESLint&hl=es-419&sa=X&ved=2ahUKEwjp0vjll6vwAhW9qJUCHZOeAWcQ6AEwAXoECAQQAg#v=onepage&q=ESLint&f=false

3.	Hands-on Nuxt.js Web Development: Build universal and static-generated Vue ...
https://books.google.com.pe/books?id=7vj3DwAAQBAJ&pg=PA464&dq=ESLint&hl=es-419&sa=X&ved=2ahUKEwjp0vjll6vwAhW9qJUCHZOeAWcQ6AEwAnoECAIQAg#v=onepage&q=ESLint&f=false


4.	Hands-on Nuxt.js Web Development: Build universal and static-generated Vue ...
https://books.google.com.pe/books?id=7vj3DwAAQBAJ&pg=PA464&dq=ESLint&hl=es-419&sa=X&ved=2ahUKEwjp0vjll6vwAhW9qJUCHZOeAWcQ6AEwAnoECAIQAg#v=onepage&q=ESLint&f=false

5.	Entre otros


Noticias

1.	NativeScript 8.0 shines on Apple M1, Webpackhttps://www.infoworld.com/article/3614852/nativescript-80-shines-on-apple-m1-webpack.html



2.	ESLint Adds ES2020 Support
https://www.i-programmer.info/news/167-javascript/13801-eslint-adds-es2020-support.html

3.	Программируем лучше с ESLint, Prettier и TypeScript
https://tproger.ru/translations/setting-up-eslint-and-prettier/

4.	Entre otros

¿Qué es PRETTIER?

Es una herramienta donde se recomienda que todos los programadores la utilicen y puedan trabajar con ella. Esta herramienta PRETTIER nos permite tener un código limpio y legible, esto es para que nosotros mismos y otras personas lo puedan leer de una mejor forma, también es para tener un código estándar para todos los programadores, por ejemplo, a mí me gusta trabajar en JavaScript con punto y coma (;) de repente a otro programador no, entonces esta herramienta me permite trabajar con un estándar (reglas).
La herramienta PRETTIER la puedes encontrar en las extensiones de Visual Studio Code y los pasos para instalarlo es la siguiente:  

1.	En la barra lateral izquierda de Visula Code Studio hay 5 botones (Explorer, Search, Source Control, Rung and Debug y las Extensions).
2.	Le damos clic en el botón Extensions
3.	Visual Studio Code te muestra un campo para ingresar la extensión, en este caso pondremos PRETTIER y el mismo Visual Studio Code te muestra una lista.
4.	Seleccionamos Prettier – Code formatter e instalamos.

¿Cómo utilizar la extensión?

Existe diferentes formas de llegar a la extensión Prettier

1.	Nos vamos al código, apretamos F1 y seleccionamos “Format Document” (Shift + Alt + F)
2.	Nos vamos al código, seleccionamos nuestro código (Ctrol + e), clic derecho sobre el código seleccionado y le damos clic “Format Document”
3.	Nos vamos al código, seleccionamos nuestro código (Ctrol + e), clic derecho sobre el código seleccionado y le damos clic “Format Selection” (Ctrol + k  Ctrol + f)

Noticias
1.	Chrome 91 Beta launches with prettier buttons, OTP autofill improvements, and battery-saving optimizations
https://www.androidpolice.com/2021/04/26/chrome-91/


2.	Free Tools That Will Help You Grow As A Front-End Developer In 2021
https://hackernoon.com/free-tools-that-will-help-you-grow-as-a-front-end-developer-in-2021-ssx334e


3.	Y el editor de código favorito de los programadores es… 8 profesionales nos dan su respuesta
https://www.xataka.com/otros/editor-codigo-favorito-programadores-profesionales-nos-dan-su-respuesta

4.	Entre otros


¿Qué es .EDITORCONFIG?

Es un plugin para tu Editor de código o IDE. Te ayuda que todos los editores que tengas, tenga la misma configuración, como un estándar, con esto se logra mantener el código consistente de manera sencilla.

Existen editores que vienen incluidos el plugin como GitHub, GitLab, Visual Studio, entre otros.

Los editores que no tienen el pluying es Atom, Brackets, CLion, Sublime Text, Visual Studio Code, entre otros.

Noticias

1.	Visual Studio 2019 v16.10 Preview 2: New Features for .NET, Containers, More
https://visualstudiomagazine.com/articles/2021/04/14/vs-2019-16-10-preview-2.aspx


2.	Visual Studio Code's C++ Extension Hits v1.0 General Availability
https://visualstudiomagazine.com/articles/2020/09/17/vscode-cpp.aspx


3.	Putting EditorConfig to Work in Visual Studio
https://www.infoq.com/news/2017/01/editorconfig-visualstudio/

4.	La version 2021.1 de Rider, I’EDI .NET multiplataforma de JetBrains está disponible:
https://jetbrains.developpez.com/actu/314106/La-version-2021-1-de-Rider-l-EDI-NET-multiplateforme-de-JetBrains-est-disponible-tour-d-horizon-des-nouveautes-et-ameliorations/

5.	Entre otros
