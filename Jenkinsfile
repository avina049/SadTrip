pipeline
{	
	agent{label 'ubuntu'}
	stages{
		stage{
			steps{
				checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/avina049/SadTrip.git']]])
			
			}
	
		}	
	
	}
}

