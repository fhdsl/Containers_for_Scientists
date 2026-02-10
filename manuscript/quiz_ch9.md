{quiz, id: troubleshooting_tips_quiz, attempts: 10}

## Understanding Docker Troubleshooting

Choose the best answer for each question.

{choose-answers: 4}
? What is one of the first questions you should ask yourself when troubleshooting Docker container issues?
C) Is there a file or software package that I'm assuming the image/container has that it does not?
m) Is my internet connection working?
m) Is Docker installed correctly?
o) Is my computer powerful enough?
o) Do I need to upgrade Docker?

{choose-answers: 4}
? When dealing with dependencies in a Dockerfile, what is a crucial consideration?
C) Make sure the dependency's RUN steps come before the software package that needs it
m) Always install all dependencies at once
m) Put all dependencies at the end of the Dockerfile
o) Skip dependency installation
o) Install dependencies in random order

{choose-answers: 4}
? When should you use the --no-cache option when building a Docker image?
C) When the base image or copied files have changed and you need to force a rebuild
m) Every time you build an image
m) Only for small images
o) Never use --no-cache
o) Only for testing purposes

{choose-answers: 4}
? What sequence of steps should you follow when debugging a Docker build issue?
C) Check for missing files, verify software packages, look for typos, and check dependencies
m) Immediately rebuild the entire image
m) Delete all containers and start over
o) Only check for typos
o) Ignore error messages

{/quiz}
