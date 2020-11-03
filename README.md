# FROM THE UDEMY SOLACE DEVELOPMENT COURSE

# Clean repo for me to play with  uwing docer and the chat application.
## from bonus repo


# Solace-chat-app-With-Docker


docker run -d -p 8080:8080 -p 55555:55555 -p 9000:9000 -p 80:80 --shm-size=2g --env username_admin_globalaccesslevel=admin --env username_admin_password=admin --name solace-dev solace/solace-pubsub-standard


localhost:8080

find the username and pw in the map
auth-server/src/main/java/com/solace/chat/application/auth/server/HashMapCredentialRepository.java

ValidUser, solace


* Navigate to http://localhost:8081/ to bring up the chat application
* Attempt login with user from HashMapCredentialsRepo.java (eg username: ValidUser password: solace)
* Notice login is successful
# Solace-chat-app-With-Docker
