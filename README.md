
Dependencias
Primero hay que instalar Node.js ya que se requiere npm para instalar tanto las dependencias como las aplicaciones

Node.js 18 LTS: https://nodejs.org/

Instalar para el SO de la máquina

Ionic 6:

npm install -g @ionic/cli@6
Angular 16.1:

npm install -g @angular/cli@16.1
Aplicaciones adicionales
Además de las dependencias hay que instalar unas aplicaciones adicionales dentro del proyecto de Ionic

JSON server:

npm install -g json-server
Levantar servidor JSON en la ruta ~src\assets\data

json-server --watch animalitos.json --host 0.0.0.0 --port 3300

Instalar BarcoDeScanner
npm install --save @ionic-native/barcode-scanner

Instalar ToastController

npm install @capacitor/toast

RegistrAPP
Aplicación para registrar asistencia por QR para DuocUC
