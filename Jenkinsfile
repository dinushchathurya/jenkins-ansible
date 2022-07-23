pipeline {
    agent any
    stages {
        stage(" execute Ansible") {
           steps {
                ansiblePlaybook (
                    installation: 'ansible', 
                    inventory: '', 
                    playbook: '/home/ubuntu/ansible-playbook/ansible.yml'
                )
            }    
        }  
    }
}