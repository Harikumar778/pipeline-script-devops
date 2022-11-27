pipeline{
    agent any
    stages{
        stage("Stage One")
        steps{
            echo "Hello from stage 1"
        }
        stage("Stage Two")
        steps{
            echo "Hello from stage 2"
        }
        stage("stage Three")
        steps{
            sh "git checkout"
        }
    }
}
