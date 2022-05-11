@Library('shared-lib') _

def config = [name: 'Manoj', dayOfWeek: 'Wednesday']

pipeline {

    agent any

    stages {

        stage('Example') {

            steps {

                helloWorld(config)

            }

        }

    }

}