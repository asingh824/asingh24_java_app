@Library('JENKINS_SHARED_LIB1') _

pipeline{

    agent any


    stages{
         
        stage('Git Checkout'){
            when { expression {  params.action == 'create' } }
        steps{
            script{
            gitCheckout(
                branch: "main",
                url: "https://github.com/asingh824/asingh24_java_app"
            )
            }
            }
        }
    }
}