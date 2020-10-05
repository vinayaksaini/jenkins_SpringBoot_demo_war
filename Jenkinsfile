node{
    stage('SCM Checkout'){
    git 'https://github.com/vinayaksaini/jenkins_SpringBoot_demo_war'
    }
    stage('Build'){
    sh 'mvn clean'
    sh 'mvn package'
    }
   }
