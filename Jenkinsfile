pipeline{
agent any
  stages{
    stage("Manage eks cluster"){
      steps{
        sh "eksctl create cluster -y cluster.yaml"
      }
    } 
   }
}
