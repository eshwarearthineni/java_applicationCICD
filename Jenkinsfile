@Library('my-shared-library') _

pipeline{

    agent any

     stages{
         
        stage('Git Checkout'){
                   
            gitCheckout(
                branch: "main",
                url: "https://github.com/eshwarearthineni/java_applicationCICD.git"
            )
            }
        }
}    