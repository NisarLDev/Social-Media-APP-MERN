# Social-Media-APP-MERN

Create one APP Web for Social Media.

## Steps followed to complete the project 

The original steps in the followed process during the first attempt until errors have arisen.

Create the environment of the project:

    1 - Create the main folders.

        1 - mkdir -p TRAVELERS_PROJECT/{client,server}
        
        2 - cd TRAVELERS_PROJECT/client
        
        3 - For create project with react: npx create-react-app ./

        Into the server folder:
        
        1 - cd TRAVELERS_PROJECT/server
        
        2 - touch index.js
        
        3 - npm init -y

        Install the dependencies:
        
        1 - npm install body-parse cors express mongoose nodemon

        2 - Added to package.json the text "type": "module",


Second attempt proven ViteJS  instead of npx create-react-app 

      1 - In the client

        Need to install the following packages:
          create-vite@4.3.1
        Ok to proceed? (y) y
        ✔ Project name: … Travelers_project
        ✔ Package name: … travelers-project
        ✔ Select a framework: › React
        ✔ Select a variant: › JavaScript + SWC

        Done. Now run:

          cd Travelers_project
          npm install
          npm run dev

         Into the server folder:
        
        1 - cd TRAVELERS_PROJECT/server
        
        2 - touch index.js
        
        3 - npm init -y

        Install the dependencies:
        
        1 - npm install body-parse cors express mongoose nodemon

        2 - Added to package.json the text "type": "module",



### Problem solved with ViteJS

Selected javascript with compilator SWC development in Rust language being much more faster than Babel during the compilation process.

Page of comparation of  yield: https://swc.rs/blog/perf-swc-vs-babel

### Finished the React inicialized


### New Structure created with ViteJS

In the new structure, the file App.jsx is equal that App.js and main.jsx is equal that index.js.

I' am changed in the file templete App.jsx in the next function for corrected error security:
 ```
 return (
            <>
              <div>
                <a href="https://vitejs.dev" target="_blank">
                  <img src={viteLogo} className="logo" alt="Vite logo" />
                </a>
                <a href="https://react.dev" target="_blank">
                  <img src={reactLogo} className="logo react" alt="React logo" />
                </a>
              </div>
              <h1>Vite + React</h1>
              <div className="card">
                <button onClick={() => setCount((count) => count + 1)}>
                  count is {count}
                </button>
                <p>
                  Edit <code>src/App.jsx</code> and save to test HMR
                </p>
              </div>
              <p className="read-the-docs">
                Click on the Vite and React logos to learn more
              </p>
            </>
          )
        }
```
## To
```
 return (
    <>
      <div>
        <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
          <img src={viteLogo} className="logo" alt="Vite logo" />
        </a>
        <a href="https://react.dev" target="_blank" rel="noreferrer">
          <img src={reactLogo} className="logo react" alt="React logo" />
        </a>
      </div>
      <h1>Vite + React</h1>
      <div className="card">
        <button onClick={() => setCount((count) => count + 1)}>
          count is {count}
        </button>
        <p>
          Edit <code>src/App.jsx</code> and save to test HMR
        </p>
      </div>
      <p className="read-the-docs">
        Click on the Vite and React logos to learn more
      </p>
    </>
  )
}

```

### Bibliography


#### Build and Deploy a Full Stack MERN Social Media App with Auth, Pagination, Comments | MERN Course:

    1 - https://invidious.nerdvpn.de/watch?v=VsUzmlZfYNg

#### React 18 Tutorial:

    2 - https://invidious.nerdvpn.de/watch?v=Flbw5BX_AX0
    
    
#### SPA con MERN: ejemplo de aplicación web


    3 - https://parzibyte.me/blog/2020/12/21/spa-mern-ejemplo-aplicacion-web/
    
    
#### Cómo crear una aplicación con el stack MERN


    4 - https://guias.donweb.com/como-crear-una-aplicacion-con-el-stack-mern/

#### MERN Stack: Qué es y qué ventajas ofrece


    5 - https://openwebinars.net/blog/mern-stack-que-es-y-que-ventajas-ofrece/


#### Solución al error "unable to resolve dependency tree While resolving..."

    6 - https://blog.pleets.org/article/soluci%C3%B3n-al-error-unable-to-resolve-dependency-tree-while-resolving

#### javascript - What does npm install --legacy-peer-deps do exactly? When is it recommended / What's a potential use case? - Stack Overflow

    7 - https://stackoverflow.com/questions/66239691/what-does-npm-install-legacy-peer-deps-do-exactly-when-is-it-recommended-wh

#### How to Use NPM --legacy-peer-deps command - Articles about design and front end development

    8 -https://weekendprojects.dev/posts/how-to-use-npm-legacy-peer-deps-command/

#### How to Use NPM --legacy-peer-deps command - Articles about design and front end development
    9 - https://weekendprojects.dev/posts/how-to-use-npm-legacy-peer-deps-command/#the---legacy-peer-deps-flag-and-react
    
    
#### Extensiones de VSCode para Javascript: descubre las mejores | Arsys

    10 - https://www.arsys.es/blog/extensiones-vscode

#### 10 Mejores extensiones de VS Code para DEVS de JavaScript – CIBERNINJAS

    11 - https://ciberninjas.com/vsc-mejores-extensiones/#1_ESLint

#### Top JavaScript VSCode Extensiones para un desarrollo más rápido 🔥 | by Wilber Ccori huaman | Medium

    12 - https://medium.com/@maniakhitoccori/top-javascript-vscode-extensiones-para-un-desarrollo-m%C3%A1s-r%C3%A1pido-2351d7b0ae23
    
    
    
###  Error encountered in project execution does not read the index.html.  Proven solution: Use VITE.js instead of create-react-app to create the project.


1 - DEJA de usar create-react-app porque ha muerto ❌ React se pasa a Vite ✅ - YouTube

    https://www.youtube.com/watch?v=GRr9pdqE5QA

2 - Migrando de Create React App a Vite - YouTube

    https://www.youtube.com/watch?v=i8SRQrflLpM

3 - Primeros pasos en React - Aprende desarrollo web | MDN
    
    https://developer.mozilla.org/es/docs/Learn/Tools_and_testing/Client-side_JavaScript_frameworks/React_getting_started


4 - Vite 4: Una nueva forma de desarrollar aplicaciones de React con SWC - YouTube

    https://www.youtube.com/watch?v=HxhHoqmgxZs

5 - Novedades de Vue 3 un año después: Vite, Pinia y más! - YouTube

    https://www.youtube.com/watch?v=5XII2X2FHsU

6 - Cómo testear los componentes de React: La guía completa
    
    https://www.freecodecamp.org/espanol/news/como-probar-los-componentes-de-react-la-guia-completa/

7 - Optimizando el Rendimiento – React

    https://es.legacy.reactjs.org/docs/optimizing-performance.html

8 - Instalación – React

    https://es.react.dev/learn/installation


9 - Create React App vs VITE vs NEXTJS ✅ Cómo CREAR un PROYECTO REACT 😎 Curso de React desde cero #2 - YouTube

    https://www.youtube.com/watch?v=KXzLyHr8UVE

### Security error corrected in the template App.jsx of ViteJS


1 - Sintaxis Markdown al completo - Cheatsheet en español

    https://markdown.es/sintaxis-markdown/

2 -Introducción a Markdown | La sintaxis de Markdown con ejemplos - IONOS

    https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/tutorial-de-markdown/

3 - Cómo utilizar Markdown para escribir documentación | Adobe Experience Cloud
    
    https://experienceleague.adobe.com/docs/contributor/contributor-guide/writing-essentials/markdown.html?lang=es

4 - Cómo dar formato al código en Markdown

    https://www.freecodecamp.org/espanol/news/como-formatear-codigo-en-markdown/

5 - Crear y resaltar bloques de código - Documentación de GitHub

    https://docs.github.com/es/get-started/writing-on-github/working-with-advanced-formatting/creating-and-highlighting-code-blocks

6 - ¿Cómo insertar código fuente de programación en las entradas de vBulletin? - BC de SiteGround

    https://www.siteground.es/kb/insertar-codigo-fuente-programacion-vbulletin/

7 - Crear snipetts adaptables para mostrar código fuente en las páginas

    https://norfipc.com/codigos/crear-snipetts-adaptables-para-mostrar-codigo-fuente-paginas.php

8 - 🚀10 Webs interesantes para probar tus Códigos Online | Consultor y Mentor estratégico | Pedro De la nube💙

    https://www.pedrodelanube.com/10-webs-para-probar-tus-codigos-online/

9 - Escribir codigo fuente en el contenido de página HTML
    
    https://desarrolloweb.com/faq/sobre-mostrar-codigo-fuente

10 - Cómo citar en HTML: <blockquote>, <q> y <cite> – CybMeta
    
    https://cybmeta.com/blockquote-q-y-cite

11 - <q>: El elemento de cita en línea - HTML: Lenguaje de etiquetas de hipertexto | MDN

    https://developer.mozilla.org/es/docs/Web/HTML/Element/q


