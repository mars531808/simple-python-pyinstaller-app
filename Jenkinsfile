pipeline {
    agent none 
    stages {
        stage('Build') { 
            agent { 'agent1' }
            steps {
                sh 'python -m py_compile sources/add2vals.py sources/calc.py' 
            }
        }
    }
}
