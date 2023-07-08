pipeline
{
    agent any
    options
    {
        buildDiscarder(logRotator(numToKeepStr: '3'))
        timestamps()
        overrideIndexTriggers(true)  
    }   
    stages
    {
        stage('Build')
        {
            steps
            {
                echo "Hello world 4"
            }
        }
    }

}
