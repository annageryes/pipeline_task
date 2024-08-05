# pipeline_task - HW2

(in the setup file , the jenkins environment is provided with workers that have docker already installed on them)

### HomeWork Requirments -> in task files

## In this repo are all the jenkins files I used in order to run this pipeline of pipelines
in order to trigger the main pipeline:
 - make sure to create a token
 -  run to trigger remotley:
    ```curl -u <JENKINS_USER>:</JENKINS_USER>KINS_PASS> <JENKINS_URL>job/<MAIN_PIPELINE_NAME>/build?token=<YOUR_TOKEN>```

## note that in the build_pipeline  you'll need to change the username and the password is not provided by default 
     
