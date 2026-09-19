pipeline{

    agent any

        stages{
            stage("Build"){
                steps{
                    bat "javac src\\calc.java"
                }
            }
            stage("Run"){
                steps{
                    bat "java -cp src\\calc"
                }
        }
        }
}