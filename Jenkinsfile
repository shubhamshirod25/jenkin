pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
  
post 
  {
    always 
    {
      emailext body: 'hello ashok', replyTo: '1ms21mc010@gmail.com', subject: 'subject', to: '1ms21mc010@gmail.com'
    }
  }
}
