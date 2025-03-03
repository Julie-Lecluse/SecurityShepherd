pipeline{
    agent any
    stages{
        stage("Checkmarx AST analysis"){
            steps{
                checkmarxASTScanner additionalOptions: '--scan-types sast,sca,iac-security',
                baseAuthUrl: '',
                branchName: 'dev',
                checkmarxInstallation: 'CxOne',
                credentialsId: '',
                projectName: 'Julie_shepherd',
                serverUrl: '',
                tenantName: '',
                useOwnAdditionalOptions: true
            }
        }
    }
}