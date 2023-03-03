pipeline 
{
    agent any
        
    
    
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
                 run 'pom.xml'
                
                 
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

