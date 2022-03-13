Steps to launch tests:
1. Launch the following command in the root directory of the entire project: 
_mvn install -DskipTests_
3. Launch the following command in the {project root}/onliner-cucumber directory: 
_mvn test_ 

Allure and cucumber reports are generated in: {project root}/test-reports.
To see Allure reports, launch the following command in the {project root}/test-reports directory (Scoop commandline-installer and Allure must be installed in the OS): 
_allure serve_
