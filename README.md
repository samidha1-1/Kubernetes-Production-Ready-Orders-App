🚀 **Kubernetes Hands-on Project 2 Completed | Making an App Production-Ready**

As part of my Kubernetes learning journey with **ESC Bash**, I successfully completed my second hands-on project.

In this project, I worked on making a basic NGINX application more reliable and ready for production using Kubernetes.

🛠️ **What I worked on:**

🔹 **ConfigMap:** Created a ConfigMap to manage application settings like `APP_GREETING` and `APP_TIER`.

🔹 **Secrets:** Created a Secret to store the `API_TOKEN` and pass it to the container.

🔹 **Deployment:** Created an `orders` Deployment with 2 replicas using `nginx:1.25-alpine`.

🔹 **Environment Variables:** Used `envFrom` and `secretKeyRef` to pass configuration and secret values to the container.

🔹 **Health Checks:** Added Liveness and Readiness Probes to check if the application is running properly and ready to receive traffic.

🔹 **Resource Limits:** Set CPU and memory requests and limits for the containers.

🔹 **Rolling Update:** Updated the NGINX image from `1.25-alpine` to `1.27-alpine` and verified that both replicas were running successfully.

💡 **What I learned:**

I understood how ConfigMaps, Secrets, Probes, Resource Limits, and Rolling Updates work together in Kubernetes.

I also learned how to update an application without interrupting its availability.

📚 Learning Kubernetes one project at a time and improving my practical skills!

Thanks to **ESC Bash** for the hands-on learning experience.

#Kubernetes #DevOps #Docker #Linux #CloudComputing #ESCbash #DevOpsJourney
