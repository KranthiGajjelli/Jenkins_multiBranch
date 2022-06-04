node('built-in') 
{
    stage('Continuous Download_loans') 
	{
    git 'https://github.com/KranthiGajjelli/Maven.git'
	}
    stage('Continuous Build_loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
