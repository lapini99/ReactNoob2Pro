# ReactNoob2Pro
React formation that includes: React basics, scss, axios and lingui

Puede que ahora te entre el miedo porque no sepas que es axios, scss o incluso React. ¡No te preocupes, mostro! Nadie nació sabiendo. Vamos a ver paso a paso cómo crear una aplicación React eficiente. Prepárate para pasar de esto de ser un tolai a un chad.

![bisho](./images/bisho.png) ![gigachad](./images/gigachad.jpg)

Así que... empecemos por el principio:

## Épica 1: React

### Capítulo 1: ¿Qué es React?

React es una biblioteca de de JavaScript que se utiliza para construit interfaces de usuario. Con React podemos montar una aplicación web con componentes reutilizables. Tener componentes reutiliazzbles nos ayuda a manter un código limpio y entendible. Se pueden crear aplicaciones de React tanto con JavaScript como con TypeScript, pero para la "formación" nos centraremos en la creación de una web app con React basada en JavaScript (JSX).

### Capítulo 2: ¿Cómo se usa React?

Puedes crear una aplicación React con el [framework](https://es.react.dev/learn/start-a-new-react-project) adecuado para tu desarrollo. Para esta pequeña formación no necesitamos liarnos y meternos en frameworks ya que a duras penas sabemos lo que es React. ¡Así que empezamos!

- 1 Abrimos una terminal en la ruta deseada y ejecutamos el siguiente comando:
  ```
    npx create-react-app myFirstApp
  ```
  Con **npx create-react-app** ejectuamos el comando que arrancará la aplicación, que en este caso se llamará **myFirstApp**. Podemos llamar la App como queramos, va a funcionar igual (eso sí, no escribas el nombre ni con espacios ni en camelCase. Utiliza snake_case o kebab-case). Yo utilizo kebab case porque tengo hambre.
  ![npx CRA](./images/npxcra.png)
- 2 Veremos que se ha creado una nueva carpeta llamada **myFirsApp**. Nos movemos a dicha ruta y abrimos nuestro IDE favorito. En mi caso voy a usar vscode así que voy a ejecutar
  `code .`  
  Veremos que se ha generado una app con una estructura de directorios y que ya es funcional.

  ![vscode1](./images/vscode.png)

  Voy a explicar brevemente lo que contiene cada carpeta:
    * node_modules: esta carpeta contiene la información que hace posible que nuestra app funcione. Es donde se almacenan todas las bibliotecas y dependencias de terceros que se descargan a través de (Node Package Manager) o yarn, que son gestores de paquetes de JavaScript.
    * public: esta carpeta contiene los archivos que serán servidos públicamente por tu servidor web y que pueden ser accedidos directamente en el navegador. El index.html que contiene es lo que va a cargar la web.
    * src: carpeta src de toda la vida. Ahí dentro vamos a meter nuestro código.

  Vale, ¿pero qué es package.json? Este contiene la información del proyecto, tal cómo scripts o liberías a instalar. Por ejemplo: si clonamos una App React desde github a nuestro pc necesitaremos ejectuar el comando `npm install` o `npm i` para así instalar las librerías necesarias para poder ejectuar el proyecto en nuestra máquina.

- 3 Llegados a este punto abrimos una terminal en nuestro IDE y ejecutamos el comando `npm run start`. Así se arrancará el proyecto. Automáticamente se abrirá el navegador con nuestra App.
![First app](./images/firstApp.png)

