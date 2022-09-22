pipeline {
	agent any
		stages{
			stage('1-clone-Sithabile'){
				steps{
					checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'github-id', url: 'https://github.com/Team3-G4-Techops/Techops-Jenkins-Project.git']]])
					sh 'ps -ef'
					sh 'sudo systemctl status jenkins'
				}
			}
			stage('2-systemcheck-roger'){
				steps{
					sh 'ps -ef'
					sh 'sudo systemctl status jenkins'			
				}
			}
			stage('3-systemcheck-constance'){
				steps{
					sh 'ps -ef'
					sh 'sudo systemctl status jenkins'
					sh 'date'
				}
			}
                        stage('4-systemcheck-kingue'){
                                steps{
                                        sh 'ps -ef'
                                        sh 'sudo systemctl status jenkins'
										sh 'date'
                               }
                        }
		}
}
