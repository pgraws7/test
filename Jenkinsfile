pipeline
{
 agent any
 stages
    {
        stage('Git clone')
       {
            steps
             {
              sh "git clone https://github.com/BASHA9692/MavenFirstApp.git"
             }
        }
        stage('Build')
       {
            steps
             {
             sh " cd /home/ec2-user/docker/workspace/docker_pipeline "
	     sh " cp -pr pom.xml /home/ec2-user/docker/workspace/docker_pipeline/"
	     sh " mvn compile"
             }
        }
      
    }
}

