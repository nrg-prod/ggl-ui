# Server Path

35.162.40.190

/var/www/html/

We deploy into Apache Web Server path.

Restart Apache service if require 

# Install NPM
npm install

# Build For Server

ng build --base-href=http://ggl.neotural.com/ --prod --aot

copy only dist folder

Do not move assert folder to server as there are many static files are uploaded mannually
