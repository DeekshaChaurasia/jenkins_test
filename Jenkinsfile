pipeline {
        agent any
        stages {
                stage('stage1') {
                        steps {
                                echo 'This is normal stage'
                        }
                }
        }
        post {
                success{
                        echo 'this post build is success'
                        echo 'this post build is success2'
                }
                failure {
                        echo 'This post build is failure'
                }
        }
}
