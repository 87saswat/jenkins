pipeline {
    agent any
    environment {
        ENV_URL = "pipeline.googlr.com"
        SAMPLE_VAR = "saswat kumar mishra"
    }
    stages {
        stage('Build') {
            steps {
                echo "Hello from saswat"
            }
        }

        stage('sample') {
            steps {
                echo "Here is a sample"
            }
        }

        stage('env-var') {
            steps {
                sh ...
                    echo My name is ${SAMPLE_VAR}
                    echo the url is ${ENV_URL}
                ...
            }
        }
    }
}