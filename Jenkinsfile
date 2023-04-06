pipeline {
    agent any
    stages {
        stage ('vcs') {
           steps {
             git url :'pipeline {
    agent any
    stages {
        stage ('vcs') {
           steps {
             git url :'https://github.com/prakashgarjagithub/EC2-ansible.git',
                 branch : 'main' 
            }
        }    
        stage ("terraform init") {
            steps {
                sh 'terraform init'
                sh 'terraform apply --auto-approve'
            }
        }
    }
