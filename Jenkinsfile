pipeline { 
    agent any
    stages {
        stage("stage") {
            when { anyOf { branch 'main'; branch 'azpoc' ; branch 'test' } }
            steps {
                echo "Hello,main"
            }
        }
    }
}
