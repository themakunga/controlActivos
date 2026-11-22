# Control de Activo Fijos

---

Aplicación y gestion de activos fijos, utilizable para arriendo/prestamo o entregas:

### Core CODE

codigo basado en _Meteor.js_ y mongoDB como administrador de base de datos, en futuras versiones se cambiará a _MYSQL_ utlizando REST.
se utiliza codigos de barra o QR para las inserciones mas rapidas. se tiene que previamente poblar la base en la seccion **_assets_**

- No usar en produccion hasta la version **1.X.XX**
- aun no se puede hacer metricas ni historial

#### packages utilizados

```
meteor-base             # Packages every Meteor app needs to have
mobile-experience       # Packages for a great mobile UX
mongo                   # The database Meteor supports right now
blaze-html-templates    # Compile .html files into Meteor Blaze views
session                 # Client-side reactive dictionary for your app
jquery                  # Helpful client-side library
tracker                 # Meteor's client-side reactive programming library

standard-minifiers      # JS/CSS minifiers run for production mode
es5-shim                # ECMAScript 5 compatibility for older browsers.
ecmascript              # Enable ECMAScript2015+ syntax in app code

## Packages no standards

kadira:flow-router
kadira:blaze-layout
erasaur:meteor-lodash
fortawesome:fontawesome
spiderable
fastclick
raix:handlebar-helpers
aldeed:collection2
aldeed:autoform
accounts-ui
accounts-password
matb33:bootstrap-glyphicons
zimme:active-route
gwendall:auth-client-callbacks
meteortoys:allthings
datariot:ganalytics
bootswatch:paper
numtel:mysql
hitchcott:qr-scanner


```

se prevee que la CSS va a ser personalizada

## Repository reference

| Path                           | Purpose               |
| ------------------------------ | --------------------- |
| [`client/`](client/)           | Client implementation |
| [`collections/`](collections/) | Meteor collections    |
| [`lib/`](lib/)                 | Shared implementation |
| [`.meteor/`](.meteor/)         | Project configuration |

The default branch is `master`. Use the tracked manifests and scripts above
when preparing changes; keep local credentials and generated files out of commits.
