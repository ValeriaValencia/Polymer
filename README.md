# \<preview-cv\>



## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

## Viewing Your Application

```
$ polymer serve
```

## Building Your Application

```
$ polymer build
```

This will create builds of your application in the `build/` directory, optimized to be served in production. You can then serve the built versions by giving `polymer serve` a folder to serve from:

```
$ polymer serve build/default
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.




## Uso
```html
<preview-cv 
  name="preview"
  nombre="Valeria Irisel" 
  cel="5531082933"
  email="valenciavaleria@outlook.com"
  edad="24"
  cumple="14 de Noviembre"
  bio= "Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500"
  viajar
  level='19'
  skills='[
    { "nombre": "JavaScript", "nivel":"50","color":"Yelow"},
    {"nombre":"HTML","nivel":"80","color":"Blue"},
    {"nombre":"CSS","nivel":"100","color":"Orange"}
  ]'
  experiencia= '[
    {
      "nombreEmpresa": "empresaX",
      "puesto": "Puesto",
      "inicio": "Junio 2018",
      "fin": "Noviembre 2019"
    },
    {
      "nombreEmpresa": "ACCASI",
      "puesto": "Soporte Tecnico",
      "inicio": "Junio 2019",
      "fin": "Septiembre 2019"
    },
    {
      "nombreEmpresa": "GFT",
      "puesto": "Trainee",
      "inicio": "Marzo 2020",
      "fin": "Actual"
    }
  ]'
></preview-cv>
```
