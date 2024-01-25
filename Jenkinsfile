node {
    stage('Checkout') {
        checkout scm
    }

    stage('Instalar Dependencias') {
        sh 'npm install'
    }

    stage('Construir') {
        sh 'npm run build'
    }
  stage('Copiar dist'){
    sh 'cp -R dist/* /Users/jorgeurgiles/prueba'
  }

    
}
