{quiz, id: containers_development_quiz, attempts: 10}

## Understanding Containers as Development Spaces

Choose the best answer for each question.

{choose-answers: 4}
? What feature of Docker allows you to use IDEs like RStudio or Jupyter notebooks from within a container?
C) The port option, which allows you to access the IDE through a browser
m) The volume option alone
m) The container ID
o) The image name
o) The container registry

{choose-answers: 4}
? When running a Jupyter notebook from a container, what command flag is used to enable JupyterLab?
C) -e JUPYTER_ENABLE_LAB=yes
m) -p JUPYTER_ENABLE_LAB=yes
m) --enable-jupyter
o) --jupyter-lab
o) -e JUPYTER=on

{choose-answers: 4}
? What is the purpose of the -v flag in the Jupyter container command?
C) It creates a volume that connects your current directory to the container's work directory
m) It specifies the container's version
m) It sets the container's password
o) It enables port forwarding
o) It installs Jupyter packages

{choose-answers: 4}
? What should you do if you need additional packages that aren't included in the development container?
C) Modify the Dockerfile to include the needed packages and rebuild the image
m) Install packages directly in the running container
m) Use a different container
o) Ignore the missing packages
o) Create a new volume

{/quiz}
