pipeline {
    agent any
    stages {

        stage("Build")
        {
            steps
            {
                script {
                        echo "INFO: Build Stage"
                        someProperty=$BAR
                        param1 = ${PARAMETER_NAME}
                    }
            }
        }

        stage("Deploy")
        {
            steps
            {
                script {
                            echo "INFO: Deploy Stage"
                    }
            }
        }
    }
}
