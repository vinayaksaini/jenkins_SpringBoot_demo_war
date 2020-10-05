node{
    stage('SCM Checkout'){
    git 'https://github.com/vinayaksaini/jenkins_SpringBoot_demo_war'
    }
    stage('Build'){
        //get maven home
        def mvnHome = tool name: 'Maven', type: 'maven'
        //sh "${mvnHome}/bin/mvn package"
        //use bat for windows - windows batch command
        bat "${mvnHome}/bin/mvn package"
        //sh 'mvn package'
    }
   }
