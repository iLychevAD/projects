# Projects
An aggregate of descriptions and links to GitHub and GitLab projects demonstrating my skills and knowledge

1. A large article where I ponder on possible scenario of migrating some existing ci\cd infrastructure on Atlassian Bamboo Server to GitLab CI:
https://gitlab.com/iLychevAD/ci-cd-for-a-multi-component-app

2. An idea about blue-green strategy for AWS Serverless (AWS Lambda + AWS API Gateway) only using CloudFormation capabilities: 
https://github.com/iLychevAD/apigw-bluegreen-cfn-gitops

3. Demonstration of my skills with ARM templates and Azure things in general - the original project was by "Microsoft patterns & practices" account but  seemed to be abandoned by the time I encountered it. In my commits I fixed ARM templates (they evolve fast and by that moment some API versions became outdated and ceased been supported by the Azure) and partially automated some steps that were manual in the original project - https://github.com/iLychevAD/serverless-reference-implementation

4. Rather simple test task demonstrating creating image processing serverless solution within AWS. One can say it uses so called [Choreography pattern](https://microservices.io/patterns/data/saga.html) -  https://github.com/iLychevAD/FacesPoC. The used API Gateway is protected by Token Lambda authorizer so you can feel safe if try to deploy the solution in your AWS account :-)

5. Nothing fancy, just one primitive test task for some employer, demonstrates my skills with CloudFormation and AWS ECS. The most interesting part is how AWS CodeBuild is used during CloudFormation Stack bootstrap process to build Docker images: 
https://github.com/iLychevAD/flask-aws-storage. Also a principal requirement was that ECS runs in an isolated from Internet subnet so a lot of VPCEndpoints has been used.

6. Long ago when it was not public I contributed a lot into that module. Before making it public they seemed to tidy up the code a lot and all my contribution was purged :-)
https://github.com/iLychevAD/ansible-module-yandex-cloud

7. That was a test task for a position of a full-stack developer (so, something not really relevant to my usual occupation but nevertheless I was curious to take on it) - https://github.com/iLychevAD/video_archive_django_celery_k8s-1. From nowadays perspective it looks really ugly and clumsy, I admit that, but I think I should not be shy for that - after all that was just a test task for which not its quality the best qualifier but amount of time the task taken to be done. Notice the repo contains a demo video.
