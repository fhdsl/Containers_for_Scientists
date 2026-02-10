
{quiz, id: using_volumes, attempts: 10}

## Using Volumes

Choose the best answer for each question.

{choose-answers: 4}
? What is a volume in Docker terminology?
C) A folder that acts like a portal between your computer and container, allowing file access
m) A type of container storage that only exists in the cloud
m) A backup system for Docker images
o) A way to permanently store files in a container
o) A special type of Docker image

{choose-answers: 4}
? Which of the following is NOT a recommended way to get files into a container?
C) Putting protected data directly into shared images
m) Using volumes to access local files
m) Using git clone to download files from online
o) Using wget to download files from online
o) Using COPY for small, necessary files


{choose-answers: 4}
? What happens to a volume when you stop and delete a container?
C) The portal/connection between the container and computer is closed
m) The files in the volume are permanently deleted
m) The volume becomes part of the container image
o) The volume is automatically backed up
o) The volume becomes read-only

{/quiz}
