pipeline{
    agent any
    environment {
        JOBTYPE = getJobType(env.JOB_NAME)
    }
    stages: {
        stage("build"){
            steps {
                echo "BUILDING"
            }
        }

        stage("test"){
            steps {
                echo "TESTING"
            }
        }

        stage("deploy"){
            steps {
                echo "DEPLOYING"
            }
        }
    }
}