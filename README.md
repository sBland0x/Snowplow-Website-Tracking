# Snowplow-Website-Tracking
This is a file made for Snowplow, illustrating implementation of their software into my personal website. 

First run 'java -jar snowplow-micro-1.2.1.jar --collector-config micro.conf --iglu iglu.json' in one CMD. 
This step will start snowplow micro and start collecting data sent to it from the website.

Then run 'http-server -p 8000' in another CMD 
Node.JS is needed in order to run this which you can either install here https://nodejs.org/en/download/ 

This program is a basic ecommerce website with a simple JS cart feature added in. The tracker is setup to track a range of different things and while improving my website I was messing around with different pre made tracking software created by snowplow which was great fun!


 window.snowplow(
      'trackPageView',

    null,
    [{
      schema: 'snowplow-micro\schema\1-0-0.json'
      data:{
        staticValue: new Date().toString()
      }
    }]

    function(){
      return [{
        
      }]
    }
    )
    Attempted to implement schemas however could not figure out how to do it in a short period of time however would love to been shown or pointed in the right direction so I can have another go in my free time! 

