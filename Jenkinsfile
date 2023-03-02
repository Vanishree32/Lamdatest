pipeline 
{
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build Application'
                bat 'mvn clean'
            }
        }

        stage('Test') 
        {
            steps 
            {
                echo 'Test Application'
            }
        }

        stage('Deploy') 
        {
            steps 
            {
                echo 'Deploy Application'
            }
        }
    }

   

    }

