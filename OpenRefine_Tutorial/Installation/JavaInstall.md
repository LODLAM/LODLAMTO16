# LODLAM Workshop: Metadata Cleaning Portion Installation Instructions
## Java requirements

### Check Your Java Version

1. Check if you have JRE already installed:
    - [Windows: Open a command (cmd) prompt](http://windows.microsoft.com/en-gb/windows-vista/open-a-command-prompt-window)
    - [Mac: Open a terminal window](https://www.youtube.com/watch?v=zw7Nd67_aFw)
    - Linux: Open a terminal window
2. Type “java -version”
3. You should see something similar to this:
    ```
    java -version
    java version "1.7.0_11"
    Java(TM) SE Runtime Environment (build 1.7.0_11-b21)
    Java HotSpot(TM) 64-Bit Server VM (build 23.6-b04, mixed mode)
    ```

Generally, Java versions 1.7 or 1.8 will work.

Mac and Linux machines will need to have Java 6 or 7 installed. If you have Java 8, and don't want to mess with Java 6 or 7, try grabbing LODRefine from GitHub and running via your command line interface of choice first, this sometimes is a work-around.

### Install Java

If you don’t have Java installed, you can download and install from:
http://java.com

### Troubleshooting Java Installation

**Java Install Path**
You may need to let your computer know where Java is installed (otherwise, commands like ‘java -version’ won't work). You do this by setting the ‘JAVA_HOME’ variable, then putting this variable in your ‘PATH’.

To do that last bit, check out these resources:

- [Brief instructions](https://docs.oracle.com/cd/E19182-01/820-7851/inst_cli_jdk_javahome_t/)
- [Windows-specific directions](https://confluence.atlassian.com/doc/setting-the-java_home-variable-in-windows-8895.html)
