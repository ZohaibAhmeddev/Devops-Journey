🐳 **Day 1 — Learning Docker**

Today I started learning Docker and focused on some of the most important concepts:

🔹 **Docker Image**  
An image is a read-only template used to create containers. It contains the application, dependencies, libraries, and configuration needed to run the application.

🔹 **Docker Container**  
A container is a running instance of an image.

The simple concept I learned:

**Image → Container → Application**

🔹 **Creating an Image**

I learned how to create a Docker image using a `Dockerfile` and:

```bash
docker build -t my-app .
```

🔹 **Creating a Container**

Then I created a container from the image:

```bash
docker run -d --name my-container my-app
```

🔹 **Checking Containers**

```bash
docker ps
docker ps -a
```

🔹 **Viewing Container Logs**

```bash
docker logs my-container
```

One important thing I learned today is that Docker container logs are associated with the container. If the container is removed, Docker-managed logs for that container can also be removed.

🔹 **Stopping and Removing a Container**

```bash
docker stop my-container
docker rm my-container
```

🔹 **Removing an Image**

```bash
docker rmi my-app
```

### 🧠 Key Concept

The biggest concept I understood today:

**Docker Image = Blueprint 📦**  
**Docker Container = Running Instance 🚀**

An image can be used to create multiple containers.

For example:

```text
             Docker Image
                  │
        ┌─────────┼─────────┐
        ↓         ↓         ↓
    Container  Container  Container
        │         │         │
       App       App       App
```

I'm continuing my DevOps journey by learning Docker, Linux, Git, CI/CD, networking, and cloud technologies step by step.

🚀 **Learning → Practicing → Building → Sharing**

#Docker #DevOps #DockerLearning #Linux #DevOpsJourney #CloudComputing #Containers #GitHub #LearningInPublic
