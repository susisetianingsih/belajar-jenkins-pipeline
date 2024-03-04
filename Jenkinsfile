pipeline {
    agent {
        node {
            label "linux"
        }
    }
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
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
