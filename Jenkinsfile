abcd=['a','b','c','d']

node('master'){
        stage('testing loop'){
                echo_all(abcd)
        }
}
def echo_all(list){
        for (int i=0;i<list.size();i++){
                sh "This is ${item}"
        }
}
