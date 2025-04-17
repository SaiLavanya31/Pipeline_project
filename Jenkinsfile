pipeline{
  agent any
  stages{
    stage('Build HelloWorld'){
      steps{
        echo 'Building HelloWorld.java'
        bat 'javac src\\main\\java\\pipeline\\HelloWorld.java'
        bat 'java -cp src\\main\\java pipeline.HelloWorld'
         }
    }
    stage('Build HelloWipro'){
      steps{
        echo 'Building HelloWipro.java'
        bat 'javac src\\main\\java\\pipeline\\HelloWipro.java'
        bat 'java -cp src\\main\\java pipeline.HelloWipro'
         }
    }
    stage('Build HelloJenkins'){
      steps{
        echo 'Building HelloJenkins.java'
        bat 'javac src\\main\\java\\pipeline\\HelloJenkins.java'
        bat 'java -cp src\\main\\java pipeline.HelloJenkins'
         }
    }
  }
}
    
