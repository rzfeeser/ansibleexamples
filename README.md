# Overview
Hey gang! Professor Feeser here. This repository contains Ansible best practice examples.


## Structure
### /playbooks
  - **precheck01.yml** - a playbook performing a basic system precheck routine
  - **precheck01-withroles.yml** - a precheck playbook that runs the `prechecks` role
  - **precheck01-collections.yml** - a precheck playbook that runs the `prechecks` role using the repository's collection-aware configuration
  - **docker01_deploy.yml** - a playbook that installs Docker, pulls an image, and launches a container
  - **marsweather-collections.yml** - a playbook that uses the `rzfeeser.nasa_api` collection to pull Mars weather data
  - **playbook-awx-project-template.yml** - a playbook that creates AWX projects and job templates
  
### /roles
  - **/prechecks/** - a role containing the reusable tasks, defaults, handlers, variables, metadata, and tests for the precheck routine


## Video Demos
Videos demonstrating the code in this repository are available on the author's [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser):  

- [YouTube CodeWithFeeser - Learn Ansible - Deploy Docker Containers with playbooks/docker01_deploy.yml](https://www.youtube.com/watch?v=Z5ktStoJrU4)

If you found a video helpful, be sure to hit **like** and **subscribe** for weekly lessons from [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser)


## How to Use This Repository
This repository is a best practice repository I use for teaching structure and organization of playbooks. If you have any suggestions, feel free to open an issue. If you haven't already, be sure to watch the video demonstrating [playbooks/docker01_deploy.yml](https://www.youtube.com/watch?v=Z5ktStoJrU4).


## Helpful Notes
- 


## Help & Training
Since 2010 I've been providing in person and online technical training solutions for large organizations and individuals. If you're looking for a training solution, reach out via my [contact portal at IRIS7](https://iris7.com/contact)
