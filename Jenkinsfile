pipeline
{
    agent any
    options
    {
        buildDiscarder(logRotator(numToKeepStr: '3'))
        timestamps()
        overrideIndexTriggers(true)  // JOb will be auto triggered when new commit is picked up
        //overrideIndexTriggers(false)  // JOb will not be auto triggered when new commit is picked up
    }   
    stages
    {
        stage('Build')
        {
            steps
            {
                echo "Hello world 7"
            }
        }
    }

}
