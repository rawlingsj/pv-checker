@Library('github.com/fabric8io/fabric8-pipeline-library@master')
def dummy
mavenNode{
  container('maven'){
    sh 'du -hc /root/.mvnrepository'
//    sh 'rm -rf /root/.mvnrepository/*'
//    sh 'du -hc /root/.mvnrepository'
  }
}
