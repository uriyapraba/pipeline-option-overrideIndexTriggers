pipeline
{
    agent any
    options
    {
        buildDiscarder(logRotator(numToKeepStr: '3'))
        disableConcurrentBuilds()
        timestamps()
        overrideIndexTriggers(true)
    }
    stages
    {
        stage('Build')
        {
            when
            {
                branch 'dev'
            }
            steps
            {
                script
                {
                    def build_number = currentBuild.number
                    echo "${build_number}"
                }
                echo "count 2"
            }
        }
    }
}