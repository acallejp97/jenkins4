pipeline {
    agent {
        dockerfile true
    }
    
    stages {
        stage('Prueba') {
	    steps {
		sh 'uname -a'
		sh 'echo hola'
	    }
        }
    }
}
