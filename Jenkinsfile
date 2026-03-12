
pipeline{
  agent any
  Stages{
    stage('checkout'){
      steps{
        git 'https://github.com/ruhi14547/my_first_repo.git'
      }
    }
    stage('publish'){
      steps{
        publishHtml({
          allowmissing:true,
          alwaysLinkedtoBuild:false,
          reportDir:',',
            reportFiles:'firsthtml.html',
            reportName:'MY Html pipe Published'
        }
       )
      }
    }
  }
}
      
