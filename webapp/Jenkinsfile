pipeline{

agent any

tools {
    maven 'Maven'
}

stages {

    stage ('Build'){

        steps{

            sh 'mvn clean package install'
        }
    }

    stage ('Test'){

        steps {

            echo "testing...."
        }
    }

    stage ('Deploy'){

        steps {
            echo "Deploying"
        }
    }
}







}