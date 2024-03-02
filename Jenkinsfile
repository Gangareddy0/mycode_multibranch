node('built-in') 
{
    stage('Continuous Download_cards') 
	{
    git 'https://github.com/Gangareddy0/mycode_multibranch.git'
	}
    stage('Continuous Build_cards') 
	{
    sh label: '', script: 'mvn package'
	}
}
