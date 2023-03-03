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
                 bat "C:\Users\Brigosha_Guest\Downloads\apache-maven-3.8.7-bin\apache-maven-3.8.7\mvn clean test"
                
                 
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

