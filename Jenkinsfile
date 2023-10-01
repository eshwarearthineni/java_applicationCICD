@Library('my-shared-library') _

pipeline{

    agent any

     stages{
         
        stage('Git Checkout'){
            steps{
            gitCheckout(
                branch: "main",
                url: "https://github.com/eshwarearthineni/java_applicationCICD.git"
            )
            }
        }
        stage('Unit Test maven'){
         
            steps{
               script{
                 
                     mvnTest()
               }
            }
        }



    }
    
}