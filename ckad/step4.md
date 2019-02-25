All operations in this question should be performed in the `ggckad-s4` namespace. 

This question will require you to create a pod that runs the image `kubegoldenguide/question-thirteen`. This image is in the main Docker repository at hub.docker.com. 

This image is a web server that has a health endpoint served at `/health` that returns a 200 status code response when the application is healthy. The application typically takes sixty seconds to start. Create a pod called `question-four-pod` to run this application, making sure to define liveness and readiness probes that use this health endpoint.
