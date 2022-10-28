pipeline {
    agent any

    parameters {
        string(name: 'INTERNAL_BASE_BUILD', defaultValue: '23000', description: '最终打包的VersionCode将由BASE_BUILD和BUILD相加确定')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}