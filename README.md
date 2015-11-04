# ASP.NET MVC 5 Demo

> Simple demo with Angular 2, Typescript, MVC 5, and WebAPI.

## Getting Started

Prepare the project, and start the Kestrel web server:

```bash
$ dnu restore
$ dnu build
$ dnx web
```

In another terminal, start a Typescript compiler process with `--watch` option:

```bash
$ npm run tsc
```

Leave this terminal to do its thing as you develop your application, but check it on occasion or if you are experiencing client-side issues as the Typescript compile may present compiler errors here.
