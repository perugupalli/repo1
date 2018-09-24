node{
    stage('SCM Checkout'){
    def mvnHome = tool name: 'Maven', type: 'maven'
    git 'https://github.com/perugupalli/repo1'
    }
    stage('Compile Packeage'){
    sh  'mvn package'
    }
}
