pipeline {
    agent any

    stages {
        stage('Verify Branch') {
            steps {
                echo "$GIT_BRANCH"
            }
        }
        stage('Verify Commit') {
            steps {
                echo "$GIT_COMMIT"
            }
        }
    }
}