node('built-in') 
{
    stage('Continuous Download_dev') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_dev') 
	{
    sh label: '', script: 'mvn clean install package'
	}
    
}
