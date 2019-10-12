node('master'){
   stage('git checkout'){
                  git 'https://github.com/allamaprabhurudraxi/INGPRODUCTS.git'
              }
   stage('java build'){
             sh 'mvn clean install sonar:sonar -Dsonar.password=admin -Dsonar.login=admin'
         }
}
