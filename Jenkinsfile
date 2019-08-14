pipeline
{
    agent any
    stages
    {
        stage('Deployment-dev')
        {
            steps
            {
                echo 'hello'
            }
        }
        stage('Deployment-QA')
        {
            steps
            {
                echo 'QA'
                input "is everything ok with staging"
            }
        }
        stage('Deployment-prod')
        {
            steps
            {
                echo 'prod'
            }
        }
    }
}
