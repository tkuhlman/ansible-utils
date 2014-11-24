#Ansible Utils
A collection of playbooks for various admin tasks

- cacert - A simple role to copy a CA cert to the remote box and add as a trusted CA
- install_python.yml - For the barebones box, install python so other Ansible playbooks can run
  - `ansible-playbook -kK -u temp_user -i hosts install_python.yml`
- setup_user.yml - Set up my user, ssh key, sudo access and some basic shell settings.
  - `ansible-playbook -kK -u temp_user -i hosts setup_user.yml`
