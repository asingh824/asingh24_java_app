//@Library('my-shared-library') _

pipeline{

    agent any


    stages{
         
        stage('Git Checkout'){
                    when { expression {  params.action == 'create' } }
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/asingh824/asingh24_java_app.git"
            )
            }
        }
    }




/*
       stages{
         
        stage('Git Checkout'){
            steps{
                script{
                    git branch: 'main', url: 'https://github.com/asingh824/asingh24_java_app.git'
                }
            }
        }
    }
}
*/
    