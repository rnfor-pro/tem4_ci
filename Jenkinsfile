pipeline {
	agent any 
		stages{
			stage('checkout from version control'){
				steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '8e554144-e3df-416e-ac98-9d989d0e4469', url: 'https://github.com/rnfor-pro/tem4_ci']]])
				}
			}
			stage('2-make a right'){
				steps{
					sh 'bash -x /var/lib/jenkins/workspace/Practical-groovy/security.sh'
				}
			}
			stage('3-make another left'){
				steps{
					sh 'echo "walk...."'
				}
			}
			stage('4-cross the street'){
				steps{
					sh 'echo "walk...."'
				}
			}
            stage('5-stop'){
				steps{
					sh 'echo "stopping now......."'
		}
}
           stage('6-call mom'){
				steps{
					sh 'echo "callinging mom right now ........."'
                }
           }

        }
}