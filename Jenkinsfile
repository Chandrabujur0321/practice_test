pipeline{
    agent any
    stages{
        stage(" greetings"){
              steps {
                echo 'Building..'
            }
        }
        stage("docker build"){
            stepes{
            sh "docker build -t test ."
            }
        }
}
}
