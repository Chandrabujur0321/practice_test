pipeline{
    agent any
    stages{
        stage(" greetings"){
            sh "hello"
        }
        stage("docker build"){
            sh "docker build -t test ."
        }
}
}
