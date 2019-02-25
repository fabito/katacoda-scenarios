# Question 5

All operations in this question should be performed in the `ggckad-s5` namespace. 

Create a file called `question-5.yaml` that declares a deployment in the `ggckad-s5` namespace, with six replicas running the `nginx:1.7.9` image.

Each pod should have the label `app=revproxy`. The deployment should have the label `client=user`. Configure the deployment so that when the deployment is updated, the existing pods are killed off before new pods are created to replace them.
