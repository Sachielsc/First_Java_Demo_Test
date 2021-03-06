# Charles' first Java script for testing
## Description
This was one of my projects maintained while I was in Planit bootcamp training. Due to the very limited number in Planit Git, I have to move it here.

I can use this script as a template for all my automation test script in Java.
## Before running
### Make sure Maven is correctly downloaded and configured before we run the scripts
- First we need to set the path for Java JDK and Maven in system variables;
  - Click [here](https://stackoverflow.com/questions/19090928/mvn-command-is-not-recognized-as-an-internal-or-external-command) to find more details
- Then we need to go to the directory that contains our pom.xml file and Run `mvn install`;
  - Click [here](https://docs.microsoft.com/en-us/azure/devops/artifacts/maven/install?view=azure-devops) to find more details

### Important update notes on 2019/08/16
Update the "groupId" and the "artifactId" in "pom.xml" file, as incorrect value for those XML elements will lead to failure.

Click [here](https://maven.apache.org/guides/introduction/introduction-to-the-pom.html) to find more about POM.

### Important notification on 2020/09/16
One major drawback of this design is that it can only run in windows, as I use a webdriver that is only compatible with browsers in windows. Same drawback also exists in the design of "DemoWorkShopTestScript" and "JUnit-Cucumber-Demo".

### Important update notes on 2020/09/17
Another major drawback of this design is that I need to manually update the webdriver file whenever my browser is updated to a new version.

### Important update notes on 2020/09/18
Important TODO: the use of "this" seems to be wrong in my "HomePage.java" and "LoginPage.java". I need to fix it when I have time.

## Other useful sites
- Click [here](https://junit.org/junit5/docs/current/user-guide/) to find more about JUnit 5
- Click [here](https://www.maketecheasier.com/vim-keyboard-shortcuts-cheatsheet/) to find more about Vim Keyboard Shortcuts Cheatsheet
- Click [here](https://guides.github.com/features/mastering-markdown/) to find more about Markdown syntax
- Click [here](https://www.gonever.com/post/25) to find more about more about .gitkeep file
