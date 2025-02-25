node('master') {
    stage('Continuous Download_Master') {
        git 'https://github.com/gurkiran333/maven24.git'
	}
	    stage('Continuous Build_Master') {
	        sh 'mvn package'
		}
}
