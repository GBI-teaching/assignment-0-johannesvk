# IntelliJ IDE
All of the following programming tasks during the tutorial will be written in the Java programming language. We recommend using an appropriate integrated development environment (IDE), such as the IntelliJ IDEA. If you have experience with Java and other IDEs you can use them but keep in mind that we can only offer limited to no assistance with these other IDEs. The following pages describe the basic installation and should be optimally be done before the first tutorial session on April 23th, 2024.

## Installation
While you can manually install the appropriate Java SDK (Version 17) we recommend letting IntelliJ install the appropriate version during Setup.
JetBrains (the company offering IntelliJ) has a students programme offering a free ultimate licence to all students and teaching staff, you can sign up for this programme but it is not mandatory, all required functions are included in the "free-for-everybody" community version of IntelliJ:

- **Optional: Education License** Register with your @student-email address. https://www.jetbrains.com/community/education/#students/

  Follow below instruction for your respective operating system:
- **Windows** users can simply download the IntelliJ installer provided on https://www.jetbrains.com/idea/download/. The installation will then be handled by the installer.
- **OSX** users simply download the 64 bit Image and move the program into their application folder. You should be able to start IntelliJ by simply clicking on the IntelliJ icon in your application folder.
- **Linux** users can use the files supplied on this link https://www.jetbrains.com/idea/download/, unpack it and run the `idea.sh` file **OR** when using snap use the following commands (for community or ultimate respectively):

  `sudo snap install intellij-idea-community --classic`

  `sudo snap install intellij-idea-ultimate --classic`

  Refer to your distribution wiki if you are uncertain how to proceed in this case.


## Basic Usage of the IDE
After the installation steps, you should be able to start the IntelliJ IDE. You should see a prompt, asking you to create a new project.

If you haven't manually installed a Java SDK you want to create a new project. In the resulting prompt basic project parameters are set. In the topmost drop-down menu, labelled "Project SDK" you should choose the "Download SDK" option, opting for the **"Oracle OpenJDK 17"** version. After a brief installation time you should be able to generate the new project.

*If OpenJDK 17 is available no additional download is required.*
<p float="left">
  <img src="https://github.com/GBI-teaching/Assignment-0/assets/45968370/79084ce9-5c8a-4576-b004-5dd37b56172d" width="600"/>
  <img src="https://github.com/GBI-teaching/Assignment-0/assets/45968370/222006cf-e24d-4a48-b582-68b0e0398487" width="400"/> 
</p>

*If not, choose Version 17, Oracle OpenJDK 17. The Location may vary.*

You can create a project based on a template (e.g. command line program) or an empty project.
In the first case a basic structure (main function, module) will be generated for you.
You can generate additional classes by right-clicking on the `src` or module folder inside of the package explorer and selecting "create a new class". 

Small Java tutorials can be found all over the web, so please inform yourself about
the basic syntax and constructs used in the Java programming language. 

We will answer questions about coding and specific problems related to the assignments. But, as this is a course about the basics in bioinformatics we cannot offer a comprehensive introduction into Java, let alone general programming.
If you do not have previous programming experience or need a refresher in Java we highly recommend investing time into tutorials - on web or otherwise.

A collection of tips and tutorials can be found on oracles homepage: http://docs.oracle.com/javase/tutorial/index.html.
