// Pipeline declarativo
pipeline {
    
    // Ejecutar desde cualquier agente (nodo) disponible
    agent any
    
    // Fases
    stages {        
        stage("Build") {            
            // Passos de la fase
            steps {                
                echo "Building artifact"                
            }            
        }        
        stage("Testing") {            
            // Passos de la fase
            steps {                
                echo "Test Unitarios..."
                echo "Test Integración..."
                echo "Test Aceptación..."                
            }            
        }        
        stage("Deploy") {            
            // Pasos de la fase
            steps {                
                echo "Deploying artifact!!!!"                
            }            
        }        
    }    
}
