node(any) {
    stage(Git clone){
        sh '''
        git branch: 'main', url: 'https://github.com/insiible-techup/jenkins-test.git'
        '''
}
   stage(List content) {
       sh '''
       ls -l
         '''
}
}
