pipeline
{
    agent any
    options
    {
        buildDiscarder(logRotator(numToKeepStr: '3'))
        disableConcurrentBuilds()
        timestamps()
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
            }
        }
    }
}