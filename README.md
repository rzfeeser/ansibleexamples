# Overview
Hey gang! Professor Feeser here. This repository contains Ansible best practice examples.


## Structure
### /
  - **precheck01-withcollections.yml** - a playbook that does not require an ansible.cfg as it uses best practice directory structure. Collections can be auto searched @ collections/ansible_collections/

### /playbooks
  - **precheck01.yml** - a playbook performing a basic precheck routine
  - **precheck01-withroles.yml** - a playbook performing a basic precheck routine using /roles/prechecks/
  
### /roles
  - **/prechecks/** - a role created from /playbooks/precheck01.yml


## Video Demos
Videos demonstrating the code in this repository are available on the author's [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser):  

- [YouTube CodeWithFeeser - Learn Ansible - Deploy Docker Containers](https://www.youtube.com/watch?v=Z5ktStoJrU4)

If you found a video helpful, be sure to hit **like** and **subscribe** for weekly lessons from [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser)


## How to Use This Repository
This repository is a best practice repository I use for teaching structure and organization of playbooks. If you have any suggestions, feel free to open an issue. If you haven't already, be sure to watch the videos I have posted on using the content found in this repository [YouTube CodeWithFeeser - Learn Ansible - Deploy Docker Containers](https://www.youtube.com/watch?v=Z5ktStoJrU4)


## Helpful Notes
- 


## Help & Training
Since 2010 I've been providing in person and online technical training solutions for large organizations and individuals. If you're looking for a training solution, reach out via my [contact portal at IRIS7](https://iris7.com/contact)
