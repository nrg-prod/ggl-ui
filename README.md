# Server Path

35.162.40.190

# Build For Server

npm install

Do this one in Local PC in Visual Studio tool

ng build --base-href=http://ggl.neotural.com/ --prod --aot
or
ng build --base-href=http://ggl.neotural.com/ --prod --aot=false --buildOptimizer=false

copy only dist folder

Do not move assert folder to server as there are many static files are uploaded mannually

/var/www/html/

We deploy into Apache Web Server path.

Restart Apache service if require 

# Install NPM
npm install



