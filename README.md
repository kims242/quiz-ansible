- name: Déployer quiz-ansible
  hosts: all
  vars: 
   ansible_python_interpreter: /usr/bin/python3
  become: true
  roles:
   - ansible-role-quiz