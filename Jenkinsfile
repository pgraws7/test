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
                cd /home/ec2-user/docker/workspace/docker_pipeline/MavenFirstApp/
                mvn compile
              }
       }
    }
}
