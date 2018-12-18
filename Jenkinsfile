pipeline {
    agent none
    stages {
        stage('Build') {
            agent {
                dockerfile {filename ‘Dockerfile.centos’}
            }
            steps {
                echo "Build Image"
            }
        }
    }
}
