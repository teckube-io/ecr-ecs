# ecr-ecs

Steps for ECR/ECS

#Step 1: 
- Create an ubuntu machine
- install docker.io
- create image
- Test on port 80 to ensure that it works

#Step 2:
- Create a user in IAM(ECR)
- Create a Policy in IAM
- Attach this policy to the user

#Step 3:
- install awscli in the machine(Step 1)
- install the user(step 2)

#Step 4:
- image-> ECR

#Step 5: ECS
- user the image of ECR
- enable port
- start the ECS Service
