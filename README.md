## Automating Laravel Application Deployment with Ansible

Application deployment can be very tedious when trying to manually deploy application over and over again. Why not have a script that can deploy your application from start to finish to save time and resources and improve productivity. This Ansible script will install application depencies in an ubuntu server, set up the database, configure redis as a message queue, configure nginx proxy, configure logging and then deploy the application.

### Prerequisites

- An Ubuntu machine
- Install Docker
- A host (remote server)