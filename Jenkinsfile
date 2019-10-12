node('master'){
   stage('git checkout'){
                  git 'https://github.com/ajitesh17/INGPRODUCTS'
              }
   stage('java build'){
             sh 'mvn sonar:sonar -Dsonar.password=admin -Dsonar.login=admin'
         }
}
