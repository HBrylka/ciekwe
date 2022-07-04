pipeline {
    agent any

    stages {

        stage('build') {
            steps {
                sh 'echo "fajny build"'
            }
        }
	stage("test"){
	     steps{
		echo 'testing app'
	}
    }
	stage("deploy"){
	     steps{
		echo 'deploy app'
	}
}
}
}
