# ansible-playbooks-1
ansible-playbooks-1

This repo has playbooks for installing nginx on servers, also installing multiple pakcages on servers/cient machines, and also to copy colour game files from controller to client's index file location. Also another playbook to install unzip and aws cli on clent machines, after checking whether they have it or not, using the output.rc for exit code. if exit code any otherthan 0, then only install these packages.
One more playbook to load credentials (encrypted) and copy files from controller to client machines, and to create users and give them a pass that is encrypted with ansible vault (ONLY THIS PART OF CODE IS NOT WORKING).


adding ansible inventory file here too.