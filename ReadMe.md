So the step by step process is:
1. setup a git repository
2. clone it to your local system.
3. fetch a hello world html code from web. 
4. write an index.html with the code.
5. write a Dockerfile for the code.
6. create a dockerhub repository. 
7. login to dockerhub in your local machine
8. build and push the image.
9. test the app on an ec2 using docker run command.
10. push the code to github
11. setup a Continuous integration pipeline on github actions that will automate the task of checkout the git repo, dockerl login, build the image, and push the image to dockerhub repository
12. test if the pipeline works properly.
13. create ecs cluster
14. create a task deifiniton with the image
15. write a github actions pipeline to deploy the image on the ecs cluster.
16. provide the sensitive information in the github repository secrets section.
17. My aws account somehow stopped setting up the network so i could not do the deployment part. sorry for that.
18. delete the infrastructure after testing.
Thank you .
