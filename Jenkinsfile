pipeline {
        agent any
        stages {
                stage('Input') {
                        input{
                                message "Is it OK to deploy the code on production"
                                ok "Yes"
                                submitter "admin"
                                parameters{
                                        string(name:'USER',defaultValue:'admin',description:'administrator')
                                }
                        }
                        steps{
                                echo "${USER}approved, processing with production deployment"
                        }
                }
        }
                                               
}
                                           
        
