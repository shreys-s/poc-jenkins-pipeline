node ('master'){
  stage 'Build and Test'
  env.PATH = "${tool 'Maven 3.3.9'}/bin:${env.PATH}"
  checkout scm
  sh 'mvn clean package'
} 
