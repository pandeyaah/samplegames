# How to implement sample game on GCP Google Compute Engine / Managed Instance Group MIG

Credits for application & Source from: https://github.com/wwwtyro/Astray for A WebGL maze game built with Three.js and Box2dWeb. 

# How to implement it in GCE

1. In GCP provision a Compute Engine instance with apache web server and use startup script(mentioned below) to install sample game from git.<br/><br/>
apt update <br/>
apt install -y git <br/>
apt install -y apache2 <br/>
cd /var/www/html <br/>
git clone https://github.com/pandeyaah/samplegames.git <br/>

2. Open http://<EXTERNAL-IP-ADDRESS-GCE>/samplegames in your browser

