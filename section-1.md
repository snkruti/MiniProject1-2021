# Why companies use Git, Dockers, automated testing, and continuous integration

Git, Dockers, automated testing, and continuous integration, all are the tools used by developers and companies, to make the development cycle more productive and efficient.

## Lest start what is Git?

<img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="212" height="212" /><img src="https://git-scm.com/book/en/v2/images/data-model-4.png" width="400" height="212" />

Git is the most popular version control system in the world. A version control system is the way to record changes made to our code over time in a special database called repository. We can look at the changes to our code made over time in a special database called repository. We can look at our project history and see who has made what changes and why. And In case something goes wrong, we can easily revert to earlier state. Without any version control System developers will have to constantly store copies of the entire project in various folders. This is very slow and doesn’t scale at all especially if multiple people have to constantly work on the same project. You would have to constantly toss around the latest code via email or some other mechanisms, and then manually merge the changes. 

## What are Dockers?
<img src="https://www.docker.com/sites/default/files/social/docker_facebook_share.png" width="212" height="212" /><img src="https://www.docker.com/sites/default/files/d8/2018-11/container-vm-whatcontainer_2.png" width="300" height="212" />

Dockers is mainly a software development platform and a kind of virtualization technology that makes it easy for us to develop and deploy apps inside of neatly packaged virtual containerized environments. Which means apps run the same, no matter where they are or what machine they are running. Dockers containers can deploy to just about any machine without any compatibility issues, so your software stays system agnostic, making software simpler to use, less work to develop, and easier to maintain and Deploy. These containers running on your computer or server act like little microcomputers. Each with very specific jobs, each with their own OS, their own CPU process, memory, and network process. Which makes it easy to add, remove, stop, and start again without affecting each other host machine. This method on containerization ensures that the application works seamlessly in any environment.

## Automated testing?
<img src="https://www.mabl.com/hubfs/TestingSystemVSTestingTool.png" width="500" height="211"/>
Automated testing is the use of tools, scripts and software to perform test cases by repeating pre-defined actions. There are two way test a software, manual and automated. Manual testing cases are executed by humans, where as automation testing use different kind of automation tools and scripts to execute test cases. Executing automation for specific tasks can be impactful and logical, rather than just applying across the site. This will also help teams to keep a control over the testing and automation process, and make it more enhancing for the overall software testing cycle. Most importantly, it makes testing more traceable and effective for teams even in the longer run.

## What is continuous Integration?
<img src="https://deploybot.com/assets/blog/_normal/continuos_integration_illustration-1.png" width="400" height="294" />
Continuous integration, or CI, is a workflow strategy that helps ensure everyone’s changes will integrate with the current version of the project. This lets you catch bugs, reduce merge conflicts, and have confidence your software is working. While the details may very depend on the development environment, most CI systems feature the same basic tools and processes. Most of the time, a team will use CI in conjunction with automated testing using a dedicated server or CI service. Whenever a developer adds new work to a branch, the server will automatically build and test the code to determine weather it works and can be integrated with the code to main development branch. The CI server will produce output containing the results of the build and an indication of weather or not the branch passes all the requirements for integration into the main development branch. This integrated code also ensures that there are no errors in the runtime environment, allowing us to check how it reacts with other changes.  

## Conclusion:

Using Dockers in organizations, continuous integration and implementation is streamlined and stabilized for increased agility of software development processes. The lightweight design of faster spun-up Docker containers encourages short test cycles. Docker quickly helps users with reliable repeatable output creation procedures such as environments. Continuous Testing is a practice in development where developers need to continually incorporate the code during a day's test plan into a shared repository. Automated builds that validate each test are produced to allow development teams to identify issues. If a continuous method is not practiced, it will take longer to integrate and correct bugs, and it will be a painful process.
