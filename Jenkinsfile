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
              sh "cd /home/ec2-user/docker/workspace/docker_pipeline/MavenFirstApp/"
              sh "mvn compile"
              sh "mvn clean package"
             }
       }
    }
}
