# Learning Activities & Resources
After the practical this week, I studied local and deployable Virtual Private Servers (VPS) tools to understand why docker, and AWS LightSail:

* Local web server stacks: https://www.superiorwebsys.com/223-local-web-server-stacks-explained-xampp-wamp-docker-lemp-and-more/
* Reason why docker is better: https://dev.to/sarahcssiqueira/10-reasons-i-moved-from-xampp-to-docker-1j6l
* AWS LightSail: https://www.iotforall.com/what-is-aws-lightsail
* AWS LightSail vs AWS EC2: https://aws.amazon.com/free/compute/lightsail-vs-ec2/
* AWS LightSail general knowledge: https://www.linkedin.com/pulse/using-aws-lightsail-its-full-potential-introduction-scalability-tdfgf/
* Docker Foundations Professional Certificate: https://www.linkedin.com/learning/paths/docker-foundations-professional-certificate

# Estimated hours
I initially spent 1 hour researching docker and AWS LightSail. After receiving the practical feedback, I spent a further 2+ hours conducting further research.

# Content Insights
Docker is an open-source platform used to build, ship, and run applications inside isolated, lightweight environments. I understand that Docker solves the problem of code running differently on other machines, by containing the entire application, code, configurations and other dependencies in one package.

AWS LightSail is an easy-to-use Virtual Private Server (VPS) provider that includes services like compute, storage, databases, and networking. This is designed for developers, small businesses, or students that need to quickly launch websites, simple applications, or web servers without complex infrastructure management. I used AWS LightSail over AWS EC2 (another VPS by AWS). This was because AWS LightSail is built for small websites, while AWS EC2 is more complex and customisable, used for enterprise applications, complex networking, large-scale systems, and high-performance computing.

Combining Docker for the local environment with AWS LightSail for the public environment supports a workflow that includes local, staging, and production setups. GitHub and GitHub Actions can then be used for version control and to automate building, testing, and deployment across these environments.

# Career/Employability/Learning Insights
Working with Docker and AWS LightSail has changed how I think about my role when working in a team. Instead of focusing only on writing code, I will consider how my work fits into shared environments where multiple developers are contributing and maintaining websites. Using consistent setups and environments will make it easier to avoid conflicts, reduce setup issues, and ensure that what I build works the same for others. It also made me more aware of how my changes can affect deployment and testing, not just my own local work.

From an employability perspective, being able to work with these tools extends my skillset beyond writing code to managing how applications run in real environments. It also supports my ability to build and demonstrate complete workflows, including local development, deployment, and updates, which are commonly expected in development roles.

From a learning perspective, I found that videos were useful for demonstrating how concepts work, but I understood the material better when I tested it myself. I preferred testing and reading through the content at my own pace, rather than relying on videos, which I found often over-explained simpler concepts.
