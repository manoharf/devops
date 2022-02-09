pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''a=1
b=2
'''
      }
    }

    stage('stage2') {
      steps {
        sh '''if [ $a == $b ]
then
echo \'a is equal to b\'
else
echo \'a is not equal to b\'
fi'''
      }
    }

  }
}
