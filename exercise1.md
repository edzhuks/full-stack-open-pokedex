Java

Linting in java can be done with CheckStyle. I have used it in university projects before and it seems similar to ESLint. It has plugins for Eclipse and IntelliJ.
Testing is usually done with the JUnit framework. Tests are written in Java with the addition of different kinds of assertions that need to hold for the test to pass.
From what I understand, the main steps of buiding in java are compiling and packaging. Compiling turns .java files into .class files which can be executed by java. Multiple files ca also be packaged into a single .jar file.

Some alternatives to GitHub Actions and Jenkins are:

-   Bitbucket Pipelines - integrated into version control, cloud based, similar to GitHub Actions.
-   AWS CodePipeline - cloud based, but not directly integrated with version control.
-   CircleCI - integrates with github, can be used in the cloud, or self-hosted.
-   Azure Pipelines - Microsoft's AWS CodePipeline equivalent.
-   GitLab - like GitHub Actions but can be self-hosted.
-   Atlassian Bamboo - like Bitbucket Pipelines, but can be self-hosted.

In my opinion it would be better to use a cloud-based environment for CI for this application. Especially if the team already uses git for version control (which they should). The effort of self-hosting would probably not be worth it for such a small team, unless they have some security concerns.
