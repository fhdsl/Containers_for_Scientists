{quiz, id: sharing_images_quiz, attempts: 10}

## Best Practices for Sharing Docker Images

Choose the best answer for each question.

{choose-answers: 4}
? What is the most important rule when dealing with protected data (like PHI or PII) and Docker images?
C) Never put protected data on publicly shared Docker images
m) Always include protected data in the image
m) Store protected data in any container registry
o) Only share protected data through public registries
o) Use default security settings for protected data

{choose-answers: 4}
? Why should you avoid creating one large Docker image for all use cases?
C) Large images are difficult to troubleshoot, take longer to build and pull, and can be hard to maintain
m) Large images are more secure
m) Large images are required for most projects
o) Large images save storage space
o) Large images load faster than small ones

{choose-answers: 4}
? Which of the following is considered a best practice for Docker image versioning?
C) Use consistent versioning tags and clearly document the versioning system you choose
m) Never use version tags
m) Use random numbers for versions
o) Keep all versions private
o) Only use single digit versions

{choose-answers: 4}
? What is an important consideration when choosing a container registry?
C) Security requirements, especially if dealing with protected data, should be the top priority
m) Always choose the most expensive option
m) Only use unknown registries
o) Ignore security features
o) Only use local storage

{/quiz}
