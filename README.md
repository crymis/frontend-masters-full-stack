# Full-Stack for Frontend-Engineers v2
__Course: https://frontendmasters.com/courses/fullstack-v2/why-full-stack/__

## Steps to start
- connect to server via ssh:
<pre>~ ssh -i ~/.ssh/deckelt_inovex-cloudGuru cloud_user@2a05:d01c:2c7:d802:e762:ace0:7657:d2a6</pre>

- install nginx:
<pre>sudo apt install nginx</pre>

- start nginx:
<pre>sudo service start nginx</pre>

- edit default nginx html:
<pre>sudo vi /var/www/html/index.html</pre>

- edit base config of nginx:
<pre>sudo vi /etc/nginx/sites-available/default</pre>

- reload nginx server
<pre>sudo service nginx reload</pre>

- start app with process manager (pm2)
<pre>pm2 start app.js</pre>

- setup a pm2 startup deamon to always start on startup of the server
<pre>pm2 startup</pre>



### Links
- express start template: https://expressjs.com/en/starter/hello-world.html
-