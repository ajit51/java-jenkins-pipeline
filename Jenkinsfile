pipeline{

    agent any

    stages{

        stage("compile"){

            steps{
                javac Main.java
            }
        }

        stage("run"){

            steps{
                java Main
            }

        }
    }

}