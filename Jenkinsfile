pipeline 
{
    agent any

    stages 
    {
        stage('Building) 
        {
            steps 
            {
                echo 'Build App'
            }
        }

        stage('Testing') 
        {
            steps 
            {
                echo 'Test App'
            }
        }

        stage('Deploying') 
        {
            steps 
            {
                echo 'Deploy App'
            }
        }
    }

    post
    {

    	always
    	{
    		emailext body: 'Summary', subject: 'Pipeline Status', to: 'selenium3bymukesh@gmail.com'
    	}

    }
}
