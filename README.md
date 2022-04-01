# task2
## Playbook 1
1- This playbook was tested on a CentOS 8 VM by runnin `ansible-playbook playbook1.yaml`
2- Home directories for each user are created automatically as the default value for the `create_home` is `yes`, so it wasn't added to the code.
3- The playbook assumes that the `wheel` group already exists on the machine
