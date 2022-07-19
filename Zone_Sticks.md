{
  "name": "MyDoc",
  "version": "1.0.0",
  "description": "MyDoc (Meu Documento) - Plataforma de Criacao e Compartilhamento de Documentos",
  "main": "index.js",
  "scripts": {
      "start": "ng serve",
      "start-poll": "ng serve --poll 5000",
      "start-docker": "npm install && ng serve --poll 5000 --host=0.0.0.0",
      "build": "ng build --configuration=dev --prod --base-href /padm/",
      "buildtest": "ng build --configuration=test --prod --base-href /padm/",
      "buildhml": "ng build --configuration=hml --prod --base-href /padm/",
      "buildprod": "ng build --prod --base-href /padm/",
      "time:server": "ng serve --poll 2000"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/Lumen-st/MyDoc.git"
  },
  "keywords": [],
  "author": "Adilson Futa",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/Lumen-st/MyDoc/issues"
  },
  "homepage": "https://github.com/Lumen-st/MyDoc#readme"
}
