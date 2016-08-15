# Install roles
        cd ansible-playbook-homerouter/ansible 
        ansible-galaxy install -r requirements.yml -p roles/ --force

# Run the playbook
       cd ansible-playbook-homerouter
       ansible-playbook playbook.yml -i inventory -b -k --ask-sudo-pass

# Finishing tasks
Just install pfSense because they do all this stuff better.
