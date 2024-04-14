# devops-automation
I developed a comprehensive CI/CD pipeline for a Java application using Jenkins and GitHub integration. The pipeline automated the entire build and deployment process.

Initially, Jenkins was configured to pull the source code from the GitHub repository whenever changes were pushed. Maven, a powerful build automation tool, was installed to manage dependencies and facilitate the build process. This ensured consistency and reproducibility across builds.

Using Maven, the Java application was compiled, tests were executed, and artifacts such as JAR files or WAR files were generated.

Subsequently, Docker was utilized to containerize the application. This involved packaging the application into a Docker image, which encapsulated the application along with its dependencies and runtime environment.

The Docker image was then pushed to Docker Hub, a cloud-based repository for storing and sharing Docker images. This step made the image accessible to other team members and deployment pipelines.

Finally, the Docker image was deployed in a Kubernetes cluster. Kubernetes provided orchestration and management capabilities, ensuring high availability and scalability of the application.

By automating these steps in Jenkins, I streamlined the development and deployment process, reducing manual effort and improving overall efficiency.