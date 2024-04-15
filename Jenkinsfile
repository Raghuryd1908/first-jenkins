pipeline{
        agent any
    stages{
        stage("Build") {
            steps{
                echo "This is Build Stage"
                sleep time: 1, unit: 'MINUTES'
            }
        }    
        stage("Test") {
            steps{
                echo "This is Test Stage"
                sleep time: 1, unit: 'MINUTES'
            }
        }
        stage("Deploymnet") {
            steps{
                echo "This is Deployment Stage"
            }
        }
    }
}
