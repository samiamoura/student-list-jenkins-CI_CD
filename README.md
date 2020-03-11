# Pipeline :  Continuous Integration / Continious Deployment with Jenkins

## Project description

- This is a complete pipeline CI/CD with **Jenkins** to deploy a python application in production
- This infrastructure it's componed of 3 servers (gitlabserver, build server and production server)
- We use Ansible, Docker, Git and Gitlab tools
- The differents stages are :
  1. Ensure lint syntax of diferents langages (bash, yamel and markdown) is OK
  2. Ensure servers are availables
  3. Ensure syntax ansible is OK with ansible-lint
  4. Build image on the build server and push artifact on the artifactory docker
  5. Deploy application on the production server
  6. Ensure application is deployed 

## Project description

![stage_jenkins](https://user-images.githubusercontent.com/58267422/76408049-a00d0300-638c-11ea-90e3-4d1c6ed72519.png)
