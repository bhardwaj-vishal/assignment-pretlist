Prerequisites: 

Needs to configure following plugins in Jenkins and called it in CI job.
1.	Pipeline Plugin 
2.	Git Plugin
3.	Nexus Plugin
4.	Maven 

Setup:-
1.	Create Github repo and add application code along with Jenkinsfile in it.
2.	Create pipeline Job in jenkins and configure it with required points below :

	a.	Add Git repo URL along with credentials (need to add it in jenkins before)

	b.	Go to Pipeline section and add SCM source to Github repo from where we added jenkinsfile and application code.

3.	Save it and build with parameter. 



