pipeline {
  stage ('Build') {
    git url: 'https://github.com/arjunamayakara/spring_rest.git'
    steps {
                bat('mvn -B -DskipTests clean package') 
            }
  }
}
