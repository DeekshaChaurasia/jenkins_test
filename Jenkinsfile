pipeline {
        agent any
        stages {
                stage('Devmaster') {
                        when{
                                anyOf{
                                        branch 'master';branch'development'
                                }
                        }
                        steps {
                               echo 'I am either Master or Development branch'
                        }
                }
                stage('master'){
                        when{
                                branch 'master'
                        }
                        steps{
                                echo 'I am master'
                        }
                }
        }
}
       
