pipeline {
    agent any
    stages{
        stage('Pull Git Demo') {
            steps{
				//拉取代码，这里也是可以使用凭据的，为了方便没贴出来
            	git credentialsId: 'GitHubLogin', url: 'https://github.com/iamtao/blog.git'
            }
        }
   }
}

