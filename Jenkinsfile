pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh '''echo \'enter file name\'
read file name
if 
then 
echo \'file exist\'
else
echo \'file not exist\'
fi'''
      }
    }

    stage('stage2') {
      steps {
        sh '''echo \'enter string\'
read string 
if [ -f $file ]
then 
echo \'string exist\'
else
echo \'string not exist\'
fi'''
      }
    }

  }
}