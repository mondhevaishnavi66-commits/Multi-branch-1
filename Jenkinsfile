pipeline{
  agent{
    label "node-1"
  }

  stages{
    stage("Hello"){
      steps{
        sh "mkdir -p A/B/C"
        sh "touch A/B/C/index.html"
      }
    }
  }
}  
