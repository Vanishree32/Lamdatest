pipeline 
{
    agent any
    tools {
        maven 'Maven 3.8.7'
        
    }
    
    environment {

    path = "C:\\WINDOWS\\SYSTEM32"

}

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'Build Application' 
                 bat 'start cmd.exe '
                 bat 'mvn clean install'
                
                 
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

