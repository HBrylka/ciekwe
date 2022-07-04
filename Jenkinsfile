pipeline {
    agent any

    stages {

        stage('build') {
            steps {
                sh 'echo "Success!"; exit 0'
            }
        }
	stage("test"){
	     steps{
		sh 'echo "Success!"; exit 0'
	}
    }
	stage("deploy"){
	     steps{
		echo 'deploy app'
	}
      post {
	always{
		echo 'this will always run'
}
	success {
		echo 'this will run only when pipeline is successful'
}
	failure {
		echo 'this will run only when pipeline is failed'
}
	unstable {
		echo 'this will run only when pipeline is unstable'
}
	changed {
		echo 'this will run only when pipeline has changed'
		echo 'For example, if the Pipeline was previously failing but now is succeded'
}
}
}
}
}
