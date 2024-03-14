pipeline
{
    agent any
    stages {
    stage('Build') {
        steps {
            // Placeholder step
            echo 'Building the project...'
        }
    }
    stage('Unit and Integration Tests') {
        steps {
            // Placeholder step
            echo 'Running unit and integration tests...'
        }
    }
    stage('Code Analysis') {
        steps {
            // Placeholder step
            echo 'Performing code analysis...'
        }
    }
    stage('Security Scan') {
        steps {
            // Placeholder step
            echo 'Performing security scan...'
        }
    }
    stage('Deploy to Staging') {
        steps {
            // Placeholder step
            echo 'Deploying to staging environment...'
        }
    }
    stage('Integration Tests on Staging') {
        steps {
            // Placeholder step
            echo 'Running integration tests on staging environment...'
        }
    }
    stage('Deploy to Production') {
        steps {
            // Placeholder step
            echo 'Deploying to production environment...'
        }
    }
}

post {
    success {
        emailext body: 'Email sent successfully !', subject: 'Jenkins mail', to: 'khushirandhawa981@gmail.com'
            
    }
}
   
}
