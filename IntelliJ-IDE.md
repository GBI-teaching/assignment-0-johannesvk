# IntelliJ IDE
All of the following programming tasks during the tutorial will be written in the Java programming language. We recommend using an appropriate integrated development environment (IDE), such as the IntelliJ IDEA. If you have experience with Java and other IDEs you can use them but keep in mind that we can only offer limited to no assistance with these other IDEs. The following pages describe the basic installation and should be optimally be done before the first tutorial session on April 23th, 2024.

## Installation
While you can manually install the appropriate Java SDK (Version 17) we recommend letting IntelliJ install the appropriate version during Setup.
JetBrains (the company offering IntelliJ) has a students programme offering a free ultimate licence to all students and teaching staff, you can sign up for this programme but it is not mandatory, all required functions are included in the "free-for-everybody" community version of IntelliJ:
\begin{itemize}
\item \textbf{Optional: Education License} Register with your @student-email address.\\ \url{https://www.jetbrains.com/community/education/#students/}
Follow below instruction for your respective operating system:
\item \textbf{Windows} users can simply download the IntelliJ installer provided on \\ \url{https://www.jetbrains.com/idea/download/}. The installation will then be handled by the installer.
\item \textbf{OSX} users simply download the 64 bit Image and move the program into their application folder. You should be able to start IntelliJ by simply clicking on the IntelliJ icon in your application folder.
\item \textbf{Linux} users can use the files supplied on this link \url{https://www.jetbrains.com/idea/download/}, unpack it and run the \texttt{idea.sh} file \bf{OR} when using snap use the following commands (for community or ultimate respectively):

\texttt{sudo snap install intellij-idea-community --classic}

\texttt{sudo snap install intellij-idea-ultimate --classic}

Refer to your distribution wiki if you are uncertain how to proceed in this case.
\end{itemize}

\section{Basic Usage of the IDE}
After the installation steps, you should be able to start the IntelliJ IDE. You should see a prompt, asking you to create a new project.

If you haven't manually installed a Java SDK you want to create a new project. In the resulting prompt basic project parameters are set. In the topmost drop-down menu, labelled ``Project SDK'' you should choose the ``Download SDK'' option, opting for the \textbf{``Oracle OpenJDK 17''} version. After a brief installation time you should be able to generate the new project.
\begin{center}
If OpenJDK 17 is available no additional download is required.\\
   \includegraphics[width=6cm]{materials/A0/new-proj.png}
   \includegraphics[width=4cm]{materials/A0/download.png}\\
   If not, choose Version 17, Oracle OpenJDK 17. The Location may vary. 
\end{center}

You can create a project based on a template (e.g. command line program) or an empty project.
In the first case a basic structure (main function, module) will be generated for you.
You can generate additional classes by right-clicking on the \texttt{src} or module folder inside of the package explorer and selecting ``create a new class''. 

Small Java tutorials can be found all over the web, so please inform yourself about
the basic syntax and constructs used in the Java programming language. 

We will answer questions about coding and specific problems related to the assignments. But, as this is a course about the basics in bioinformatics we cannot offer a comprehensive introduction into Java, let alone general programming.
If you do not have previous programming experience or need a refresher in Java we highly recommend investing time into tutorials - on web or otherwise.\footnote{A collection of tips and tutorials can be found on oracles homepage: \url{http://docs.oracle.com/javase/tutorial/index.html}}.