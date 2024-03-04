pipeline {
    agent {
        node {
            label "linux"
        }
    }

    stages {
        stage('Build') {
            steps {
                echo 'Hello Build'
            }
        }
        stage('Test') {
             steps {
                echo 'Hello Test'
             }
        }
        stage('Susi') {
             steps {
                ech 'Hello Susi'
             }
        }
        stage('Deploy') {
             steps {
                echo 'Hello Deploy'
             }
        }
    }

    post {
        always {
            echo "alhamdulillah jalan"
        }
        success {
            echo "alhamdulillah sukses"
        }
        failure {
            echo "astaghfirullah gagal, belum rejeki"
        }
        cleanup {
            echo "akan selalu jalan tapi diakhir"
        }
    }
}
