# wc-htmx framework

the vanilla js framework - only compiled by the ts compiler

## devBuild

- TODO: on change of any file launch devbuild script
- TODO: devbuild script checks all .js files for HTMLElement classes and looks for the template property
- TODO: devbuild script checks all .html files `npx tailwindcss -i ./src/css/main.css -o ./dist/css/output.css --watch` to create the minimal css

## devServe

- TODO: serves the devBuild

## easyWebComponent

- TODO: create class that can be extended to make rendering easy by using the initRender by default to allow for tailwind
- TODO: create equivalent of useState that forces a render when setState is called
