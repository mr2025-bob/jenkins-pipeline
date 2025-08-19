pipeline {
    agent any
    stages {
    stage('clone') {
        steps{
            sh echo 'echo"clone"'
        }
    }
    stage('test'){
        steps{
        echo 'echo "test"'
    }
}
    stage('createfile'){
        steps{
            sh 'touch text-$BUILD_ID'
        }       
    }
   }

}