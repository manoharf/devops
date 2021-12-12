pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''a=1
b=2
if [ $a == $b ]
then
echo \'a is equal to b\'
else
echo \'a is not equal to b\'
fi'''
      }
    }

    stage('stage2') {
      steps {
        sh '''a=1
c=2
is [ $a == $c ]
then
echo \'a is equal to c\'
else
echo \'a is not equal c\'
fi'''
      }
    }

  }
}