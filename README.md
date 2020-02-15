# mirror-content-for-disconnected-openshift-install
This is playbook to mirror needed contents for a complete disconnected openshift installation

To use this repository run the following command to clone required roles. 
```
ansible-galaxy install -r requirements.yml --roles-path=roles
```
Then provide update intentory file to match your envirornment. 
Finally run the playbook.
