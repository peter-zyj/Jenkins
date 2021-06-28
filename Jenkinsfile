pipeline {
    agent any

    stages {
        stage('Build_Geneve') {
            steps {
                echo 'Platform: '
                echo 'Test Version: '
                echo 'Test Product: '
                echo 'Build Test Bed'
            }
        }
        stage('Test_Geneve') {
            steps {
                echo 'Run Pytest'
            }
        }
        stage('Report_Geneve') {
            steps {
                echo 'Upload Test Result to InfluxDB'
            }
        }
    }
}
