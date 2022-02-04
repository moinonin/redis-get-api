# Installation
Install the package from PyPi with `pip install redis-get-api`.  
# Usage 
The redis-get-api package comes handy when you want to use api endpoints that have restricted rate limits. It does  
exactly that by enforcing rate limits while preserving persistence in the local redis database for the required time limit.  
For instance if you are building upon twitter, and you intend to search tweets, you are only allowed say 450 requests within any  
15 minutes interval. This package will fetch the first result and cache it for the next 15 minutes when you are not allowed to hit the twitter API  
directly.  
## Requirements and parameters
You must install redis to use this application. You can use the application as a commandline interface for testing purposes, or within your scipt.



