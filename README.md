# aws-sam-project
- To run SAM project locally:
  - Run Docker
  - cd to project home
     - DOCKER_HOST=unix://$HOME/.docker/run/docker.sock sam local invoke PostHandlerLambdaFunction --event events/event.json   
  - Run logs locally:
     - sam logs --stack-name PhotoAppUsersRestAPI   
