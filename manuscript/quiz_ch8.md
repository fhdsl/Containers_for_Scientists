{quiz, id: cleaning_up_quiz, attempts: 10}

## Understanding Docker Cleanup Operations

Choose the best answer for each question.

{choose-answers: 4}
? Why is it important to clean up Docker containers and images periodically?
C) They take up space on your computer and can cause performance issues if too many accumulate
m) They automatically expire after a certain time
m) They slow down the internet connection
o) They interfere with other Docker installations
o) They cause security issues if not removed

{choose-answers: 4}
? What is the correct order of operations when removing Docker images and containers?
C) First stop and remove containers, then remove the associated images
m) Remove images first, then remove containers
m) Remove everything at once without checking
o) Only remove containers and keep all images
o) Only remove images that aren't being used

{choose-answers: 4}
? What command would you use to remove all non-running Docker containers?
C) docker rm $(docker ps -a -q)
m) docker rmi $(docker ps -a -q)
m) docker stop $(docker ps -a -q)
o) docker delete $(docker ps -a -q)
o) docker remove $(docker ps -a -q)

{choose-answers: 4}
? What happens if you try to remove a Docker image that is currently being used by a running container?
C) The removal will not be allowed until the container is stopped and removed
m) The image and container will both be automatically removed
m) Only the container will be removed
o) The system will crash
o) The image will be partially removed

{/quiz}
