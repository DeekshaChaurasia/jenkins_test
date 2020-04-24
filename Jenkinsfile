pipeline {
        agent any
        
        stages {
                stage('normal stage') {
                        steps {
                                echo "this is normal stage"
                               
                        }
                }
                stage('paraleele stage'){
                        parallel{
                                stage('parallelstage1'){
                                        steps {
                                                echo 'This is parallel stage 1'
                                        }
                                }
                                 stage('parallelstage2'){
                                        steps {
                                                echo 'This is parallel stage 2'
                                        }
                                }
                                stage('parallelstage3'){
                                        steps {
                                                echo 'This is parallel stage 3'
                                        }
                                }
                                stage('parallelstage4'){
                                        steps {
                                                echo 'This is parallel stage 4'
                                        }
                                }
                        }
                }
        }
}
     

