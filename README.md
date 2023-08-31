# How to use this repository?

1. Create a new Jenkins job:<br />
From the Jenkins dashboard, click on "New Item" to create a new Jenkins job.<br />
Enter a suitable name for the job and select "pipeline".<br />
Click on "OK" to proceed.<br />

2. Configure the Jenkins job:<br />
In the job configuration page, scroll down to the "GitHub project" section.
Check the box.<br />
Provide this Git repository URL.<br />
Next scroll down to the "GitHub hook trigger for GITScm polling" section.
Check the box.<br />

3. Create the script: Scroll down to the pipeline definition and select "Pipeline script".</br>
Copy and paste the script called jenkins_script from this repo into the text-field.</br>
Save the configuration.<br />
4. Build the Jenkins job:<br />
From the Jenkins dashboard, locate and click on the job you created.
Click on "Build Now" to start the job.
Jenkins will clone the Git repository, execute the build steps, and print the console messages with the environment variables.

## First result
![alt text](pics/result_one.png)
As you may see the message: Hi, Cristian Rojas made thiss! is displayed
## Second result
![alt text](pics/result_two.png)
After the code modification the message: This is a modification, Cristian Rojas made thiss! is displayed
## Builds
![alt text](pics/builds.png)
## Last pipeline steps
![alt text](pics/pipeline_steps.png)