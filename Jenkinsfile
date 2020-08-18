

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
                powershell script: 'ls env:'
                //checkout([$class: 'GitSCM', branches: [[name: env.job_base_name]], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[url: 'https://github.com/yoav-klein/Multibranch.git']]])
                echo "Master branch"
            }
        }
    }
}
