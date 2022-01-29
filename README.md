# Snowplow-Website-Tracking
This is a file made for Snowplow, illustrating implementation of their software into my personal website. 

First run 'java -jar snowplow-micro-1.2.1.jar --collector-config micro.conf --iglu iglu.json' in one CMD. 
This step will start snowplow micro and start collecting data sent to it from the website.

Then run 'http-server -p 8000' in another CMD 
Node.JS is needed in order to run this which you can either install here https://nodejs.org/en/download/ 