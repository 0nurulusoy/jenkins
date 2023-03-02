Here are the steps to follow:

- In the Jenkins dashboard, navigate to the desired Jenkins job and click "Configure".
- Scroll down to the "Pipeline" section and select "Pipeline script from SCM" in the "Definition" dropdown.
- Choose "Git" as the SCM, and enter your GitHub repository URL https://github.com/devopsrange/jenkins .
- Leave the "Credentials" field empty.
- Set the "Script Path" to the path of the Jenkinsfile in your GitHub repository (e.g., Jenkinsfile).
- Click "Save" to save your pipeline configuration.
- Once saved, Jenkins will automatically fetch the Jenkinsfile script from your public GitHub repository and execute it whenever the Jenkins job is triggered.
