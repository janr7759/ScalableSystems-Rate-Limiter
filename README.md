# scalable_systems_design
# Reference:  https://blog.cloudflare.com/counting-things-a-lot-of-different-things/
Project 1

## System with stream of requests along with their timestamps
   each mesage hould only be printed at most every 10 seconds; messages come in chronological order
   multiple messages arrive at the same timestamp
   Implement logger class:
   
   Logger() ## to initialize logger (python)
   
   want a hashmap, the key of hashmap is actual message
   what they store is actual timestamp they see that message
   
   
   
   adding throttling or rate limiting mechanism that allow only a certain number of requests so can respond to all of them
   rate limiter, limits the number of requests; can handle certain # then caps the requests
