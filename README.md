# Nginx Fine Tuning
 
## Docker 
Run docker container from main project folder 
`docker-compose up`

# How to use it 
# Command for request image:
`curl -D - localhost/images/cracking-the-code.jpg --output for-cached.jpg` 

# Command for purge image: 
`curl -D - localhost/images/cracking-the-code.jpg --output for-cached.jpg -H "update-cache:true"` 
 
