Readme: 

1. To test the application, paste the "ansible-playground" repository on a ansible host. 
2. Define your target hosts inside "hosts" under "/ansible-playground".
3. Ansible roles are defined inside "/roles". There are 2 roles: "install_NMAP" role which does the installation of the NMAP utility and "prepare_target_hosts" which checks and deploy python3. "prepare_target_hosts" role should be used only for the first ansible run. 
4. To start the installation of NMAP utility, run the command: "ansible-playbook install.yml -i hosts". 
