pipeline{
        agent any
        stages{
            stage('Make Directory'){
                steps{
                    sh "mkdir -p ~/jenkins-freestyle-project"
                }
            }
            stage('Make Files'){
                steps{
                    sh "touch ~/jenkins-freestyle-project/file1 ~/jenkins-freestyle-project/file2"
                }
            }
        }
}
