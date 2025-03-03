pipeline{
    agent any
    stages{
        stage("Checkmarx AST analysis"){
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