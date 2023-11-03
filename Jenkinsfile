@Library('my-shared-library') _

pipeline{

    agent any

    stages{
        stage('Git Checkout'){

            steps{
            gitCheckout(
                gitCheckout(
                    branch: "main"
                    url: "https://github.com/asingh824/asingh24_java_app.git"
                )
            )
            }
        }
    } 
}
    