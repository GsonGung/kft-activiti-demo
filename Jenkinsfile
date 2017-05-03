node ('test'){ 
  stage("checkout"){
		git branch: '${BRANCH_NAME}', credentialsId: '', url: 'https://github.com/GsonGung/kft-activiti-demo'
	}
	stage('build'){
		sh "mvn clean install deploy"
	}
}
