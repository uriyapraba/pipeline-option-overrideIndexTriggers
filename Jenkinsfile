pipeline
{
    agent any
    options
    {
        buildDiscarder(logRotator(numToKeepStr: '3'))
        timestamps()
        overrideIndexTriggers(false)  
    }   
    stages
    {
        stage('Build')
        {
            steps
            {
                echo "Hello world 1"
            }
        }
    }

}
