@Library('github.com/fabric8io/fabric8-pipeline-library@master')
def dummy
mavenNode{
  sh 'du -hc /var/lib/jenkins'
  container('maven'){
    sh 'du -hc /root/.mvnrepository'
//    sh 'rm -rf /root/.mvnrepository/*'
//    sh 'du -hc /root/.mvnrepository'
  }
}
