# Playbooks

Similar to Ansible Roles Salt uses sls files.
    
SLS files are locater on thevMaster at 

      /srv/salt

### To run an sls file from the Master to the Minions simply 
      run salt '*' state.apply vim
