# ansibleexamples
Examples of Ansible best practice

## /
  - **precheck01-withcollections.yml** - a playbook that does not require an ansible.cfg as it uses best practice directory structure. Collections can be auto searched @ collections/ansible_collections/

## /playbooks
  - **precheck01.yml** - a playbook performing a basic precheck routine
  - **precheck01-withroles.yml** - a playbook performing a basic precheck routine using /roles/prechecks/
  
## /roles
  - **/prechecks/** - a role created from /playbooks/precheck01.yml
