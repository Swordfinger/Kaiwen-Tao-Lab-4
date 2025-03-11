# Kaiwen-Tao-Lab-4

## AI Disclosure Form
Refer to the L4_AI_Declaration_Kaiwen_Tao_301551216.pdf

## Github Skills

![b169703c9aae13080898912ff676a88](https://github.com/user-attachments/assets/b42173a6-24d4-447b-a55d-6c2981daa7fd)

![43a60084f2a23328cf6cfa7dd44db34](https://github.com/user-attachments/assets/fc8be7c1-9609-4997-839f-7a891b5780f9)

# Docker Videos + Questions

1. Explain in your own words why Docker can be beneficial for developers working in teams.

Docker can be beneficial for developers on a team because it eliminates the problem of project development teams being unable to test and run the application because different team members have different operating systems, package versions, or dependencies. If I made an application in a Node.js environment. To run it, I need to download a version of the environment that has a specific feature, but while I can run it after setup, other team members' computers can't run it because they have different operating systems, package versions, or dependencies that can't be tested. So I need to match the version with the team members so they can run it. To make sure the app runs correctly on other team members's computers, it will take a whole lot of procedures to do; this will require a cagey long setup process. With Docker, on the other hand, you can package everything you need for your application, including specific Node.js versions, dependencies, and configurations, into a single container. This way, every team member can run the exact same environment, regardless of their operating system or setup.

2. Compare and contrast Docker containers and virtual machines as discussed in the video. What are some key differences in how they manage resources and dependencies?

The virtual machines have their own full operating system that runs on top of the host computer, but the containers share the host computer's instead of the operating system's kernel, which makes it more lightweight than virtual machines and less bloated. Therefore, they are typically quicker to start up, and they use less memory on computers, although both can solve the same problems.

3. Discuss the significance of Docker images being read-only. How might this feature be advantageous or disadvantageous in application development?

An image is like a blueprint for the container, which stores the runtime environment, application code, dependencies, additional configurations and commands. The advantage of the image feature is that it guarantees the consistency of the environment and because the image is read-only, so there is no possibility of modifying it or performing additional steps. The disadvantage is that the image cannot be modified, so in case of an error in the image, the only option is to create a new one. However, I think the advantages of images outweigh the disadvantages, because for steps such as unifying the development environment, I think images greatly reduce the risk of unpredictable installation errors.
