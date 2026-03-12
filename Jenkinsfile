pipeline{
  agent any
    stages{
      stage('Checkout'){
        steps{
          git 'https://github.com/ruhi14547/my_first_repo.git'
        }
      }
      stage('Publish'){
        steps{
          publishHTML([allowMissing:true, alwaysLinkToLastBuild:false, keepAll:false, reportDir:'.', reportFiles:'firsthtml.html', reportName:'ABC'])

}
}
}
}
