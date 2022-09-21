pipeline {
    agent any
    stages {
        stage("buil") {
            steps {
                echo "build the code"
            }
        }
        stage("test") {
            steps {
                echo "testing the code"
                echo "testing scan too"
            }
        }
        stage("deploy") {
            steps {
                echo "deploying code"
            }
        }
    }
}
