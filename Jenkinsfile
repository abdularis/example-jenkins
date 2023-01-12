pipeline {
    agent any
    stages {
        stage("Lint") {
            steps {
                echo "Code linting running..."
                echo "Lint done"
            }
        }

        stage("Build") {
            steps {
                echo "Preparing for builds..."
                echo "Build successful"
            }
        }

        stage("Test") {
            steps {
                echo "Testing new build..."
            }
        }
    }
}