# task2
## Playbook 1
1- This playbook was tested on a CentOS 8 VM by running `ansible-playbook playbook1.yaml`  
2- Home directories for each user are created automatically as the default value for the `create_home` is `yes`, so it wasn't added to the code.  
3- The playbook assumes that the `wheel` group already exists on the machine  

## Playbook 2
1- This playbook was tested on a CentOS 8 VM by running `ansible-playbook playbook2.yaml --extra-vars='{"target":"IP","target_user":"USER","target_pass":"PASS"}'`
2- The remote server has the following OS properties
  NAME="Red Hat Enterprise Linux Server"
  Version="7.4 (Maipo)"
  ID="rhel"
  VARIANT="Server"
