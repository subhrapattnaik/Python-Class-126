# Python-Class-126

Ngrok is a useful utility to create secure tunnels to locally hosted applications using a reverse proxy. It is a utility to expose any locally hosted application over the web.


In simple terms, it provides a publicly accessible web URL to any locally hosted application i.e. be it a Spring boot or nodejs based web application or a webhook for a chat application, etc.


some say it as “N G rok” while a lot of people prefer “en-grok”




Download and Install
https://ngrok.com/download



A brief description of the numbered arrows above is given below:

Run the local app, so that it can be accessed at your localhost.  Example: http://localhost:8080
Now with ngrok executable (available for different platforms like Mac, Windows, etc.) initiate a tunnel to the localhost on the desired port. We will see this detail in the upcoming sections.
Once ngrok sets up the tunnel, it provides a web-accessible URL.
Now share the publicly accessible url with the end-users who would hit the locally hosted application.
End users hit the web URL on the internet.
When the request arrives at the ngrok server (As the URL is in a subdomain of ngrok.com the requests will initially land to ngrok server), and it will resolve the URL to the app that it needs to tunnel to.
Ngrok forwards the request to the tunnel created in Step 2.
The forwarded request connects to the locally hosted app.
Mentioned above is the sequence of steps that take place when a locally hosted app is accessed using ngrok.


