peline {
    agent any
ddjjjlkjlhohnnm kjbkhbhkhbkjn n kjb khbjhbhjbhkbh
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello Test stage'
            }
        }
        stage('Prod') {
            steps {
                echo 'Hello Prod stage'
                build quietPeriod: 4, job: 'Job1'
            }
        }
    }
}
