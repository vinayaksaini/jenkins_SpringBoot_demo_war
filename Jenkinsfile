node{
    stage('SCM Checkout'){
    git 'https://github.com/vinayaksaini/jenkins_SpringBoot_demo_war'
    }
    stage('Build'){
        //get maven home
        def mvnHome = tool name: 'Maven', type: 'maven'
        bat "${mvnHome}/bin/mvn package"
        //sh 'mvn package'
    }
   }
