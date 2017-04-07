node {
openshift.pod('buildpod').withImage('maven').withSecret('gpg-key','/home/jenkins/.gnupg').inside {      
    git 'https://github.com/dmarley/tfrs-sonar-scanner.git'
    sh 'mvn clean install'
}
}
