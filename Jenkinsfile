pipeline{
    agent any
    environment {
        JOBTYPE = getJobType(env.JOB_NAME);
        // BITBUCKET_COMMON_CREDS = credentials('jenkins-bitbucket-common-creds')
    }
    stages {
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