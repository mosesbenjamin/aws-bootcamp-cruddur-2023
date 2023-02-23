# Week 1 — App Containerization

## Required Homework

### Containerize Application (Dockerfiles, Docker Compose)
[Containerized application backend](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/backend-flask/Dockerfile)

![Containerized backend](assets/proof-of-containerized-backend-app.png)

[Containerized application frontend](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/Dockerfile)

![Containerized frontend](assets/proof-of-containerized-frontend-app.png)

[Docker compose file at the root of the project](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/docker-compose.yml)

![Containerized applications working in tandem](assets/proof-of-docker-compose-and-that-services-work-in-tandem.png)

### Document the Notification Endpoint for the OpenAI Document
[Notification endpoint for OpenAPI doc](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/backend-flask/openapi-3.0.yml#:~:text=/api/activities/notifications,schemas/Activity%27)

![Notification Endpoint for the OpenAI Document](assets/proof-of-notification-endpoint-for-openapi-doc.png)

### Write a Flask Backend Endpoint for Notifications
[Notifications Activities service](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/backend-flask/services/notifications_activities.py)

![Flask Backend Endpoint for Notifications](assets/proof-of-flask-backend-endpoint-for-notifications.png)

### Write a React Page for Notifications
[Notifications Feed Page](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/src/pages/NotificationsFeedPage.js)

![React Page for Notifications](assets/proof-of-react-page-fornotifications.png)

### Run DynamoDB Local Container and ensure it works

![DynamoDB Local Container works](assets/proof-that-dynamodb-local-container-works.png)

### Run Postgres Container and ensure it works

![Postgres Container works](assets/proof-that-postgres-container-works.png)

## Homework Challenges

### Run the dockerfile CMD as an external script
[Backend Dockerfile](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/backend-flask/Dockerfile)

[Backend script file](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/backend-flask/script.sh)

[Frontend Dockerfile](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/Dockerfile)

[Frontend script file](https://github.com/mosesbenjamin/aws-bootcamp-cruddur-2023/blob/main/frontend-react-js/script.sh)

![Dockerfile CMD as an external script](assets/proof-of-cmd-running-as-an-external-script.png)

### Push and tag a image to DockerHub (they have a free tier)

![Tagging and pushing to dockerhub](assets/proof-of-tagging-and-pushing-to-dockerhub.png)

![Backend image in dockerhub](assets/proof-of-backend-image-in-dockerhub.png)

![Frontend image in dockerhub](assets/proof-of-frontend-image-in-dockerhub.png)

### Use multi-stage building for a Dockerfile build

(remember to add proof)
