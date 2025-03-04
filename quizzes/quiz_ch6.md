
{quiz, id: write_dockerfiles, attempts: 10}

## Write Dockerfiles

Choose the best answer for each question.

{choose-answers: 4}
? When installing packages in a Dockerfile, what is an important syntax consideration?
C) Using backslashes () at the end of each line for continuing commands and maintaining proper spacing
m) Using semicolons at the end of each line
m) Adding spaces randomly throughout the command
o) Using forward slashes (/) at the end of each line
o) Adding extra blank lines between commands

{choose-answers: 4}
? What is the recommended approach when looking to add new software to your Dockerfile?
C) Look for other Dockerfiles with the same base OS and copy their successful installation steps
m) Always write installation steps from scratch
m) Only use the newest versions of software
o) Avoid using version numbers
o) Only use default package managers

{choose-answers: 4}
? If you're planning to use R in your container, which image repository should you specifically look at first?
C) rocker images
m) Python images
m) Ubuntu base images
o) Alpine images
o) Node images

{choose-answers: 4}
? What is a recommended practice when specifying package versions in a Dockerfile?
C) Always specify version numbers to ensure consistent rebuilds
m) Never specify version numbers
m) Only specify major version numbers
o) Use random version numbers
o) Let the package manager choose versions automatically

{/quiz}
