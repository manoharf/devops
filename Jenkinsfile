pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''a=1
b=2
echo \'a is equal to b\'
echo \'a is not equal to b\''''
      }
    }

    stage('stage2') {
      steps {
        sh '''a=1
b=1
echo \'a is equal to b\'
echo \'a is not equal b\''''
      }
    }

  }
}