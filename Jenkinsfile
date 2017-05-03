node ('test'){ 
  stage("checkout"){
		git branch: '${BRANCH_NAME}', credentialsId: '317a375f-d09f-45e0-ae3d-bb39510932c6', url: 'https://github.com/GsonGung/kft-activiti-demo'
	}
	stage('build'){
		sh "mvn clean install deploy"
	}
}
