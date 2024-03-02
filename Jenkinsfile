node('built-in') 
{
    stage('Continuous Download_cards2') 
	{
    git 'https://github.com/Gangareddy0/mycode_multibranch.git'
	}
    stage('Continuous Build_cards2') 
	{
    sh label: '', script: 'mvn package'
	}
}
