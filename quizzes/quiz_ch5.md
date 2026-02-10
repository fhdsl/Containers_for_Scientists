
{quiz, id: modifying_containers, attempts: 10}

## Modifying Containers

Choose the best answer for each question.

{choose-answers: 4}
? What is a Dockerfile primarily used for?
C) It's a recipe that describes how to build a Docker image
m) It's a way to run containers
m) It's a tool for storing container data
o) It's a program to download Docker images
o) It's a security protocol for Docker

{choose-answers: 4}
? What is the recommended strategy for creating Docker images regarding size?
C) Start with the smallest possible image and add only what you need for specific cases
m) Always include all possible packages you might need
m) Create one large image for all use cases
o) Only use pre-built images
o) Always start with the largest base image

{choose-answers: 4}
? What is the difference between the FROM, CMD, and RUN commands in a Dockerfile?
C) FROM creates a layer from another image, CMD specifies the default command to run at start, RUN executes commands during build
m) They are all the same command with different names
m) FROM runs commands, CMD creates layers, RUN specifies defaults
o) They are only used for package installation
o) They only work with base images

{choose-answers: 4}
? What is the correct format for installing R packages from CRAN in a Dockerfile?
C) RUN Rscript -e "install.packages(c('package_name'))"
m) CMD Rscript -e "install.packages(c('package_name'))"
m) FROM Rscript -e "install.packages(c('package_name'))"
o) INSTALL Rscript -e "install.packages(c('package_name'))"
o) ADD Rscript -e "install.packages(c('package_name'))"

{/quiz}
