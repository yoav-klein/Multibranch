

pipeline
{
    agent 
    {
        label 'master'
    }

    stages
    {
        stage('First')
        {
            steps
            {
                script {
                    println env.job_name
                }
                //checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/yoav-klein/Multibranch.git']]])
                echo "Master branch"
            }
        }
    }
}
