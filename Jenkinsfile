pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Verify Tag') {
            steps {
                echo "$GIT_TAG"
            }
        }
        stage('Verify Commit') {
            steps {
                echo "$GIT_COMMIT"
            }
        }
    }
}