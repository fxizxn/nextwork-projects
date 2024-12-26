### NextWork.org

# Set Up a Web

# App in the

# Cloud

#### fxizxn.dev@gmail.com


#### NextWork Student NextWork.org

## Introducing Today's Project!

### What is VSCode and why is it useful?

VSCode made this project more efficient by providing a PowerShell terminal.
(Windows) and connecting to an EC2 instance remotely in VSCode. Using Remote -
SSH extension, it becomes possible to access and edit files directly within the
window.

### How I'm using VSCode in this project

VSCode made this project more efficient by providing a PowerShell terminal.
(Windows) and connecting to an EC2 instance remotely in VSCode. Using Remote -
SSH extension, it becomes possible to access and edit files directly within the
window.

### One thing I didn't expect...

The challenge facing while connecting the EC2 instance into VSCode. Though it
seems easy, but being on a Windows machine, it becomes quite difficult. I've
learnt to connect EC2 instance into VSCode.

### This project took me...

It took me around 1.5 hours + some downtime when I faced the EC2 instance.
breakdown and then recreating it over again.


#### NextWork Student NextWork.org

## Launching an EC2 instance

I launched this EC2 instance to host my web app for the devops project. This is
the first step to initialise an EC2 instance in a region, which will be used for the
rest of the project.

### I also enabled SSH.

SSH is a secure shell, which is a protocol that ensures communication between
servers (connected remotely) is authorised and secure. I enabled SSH traffic so
that I can connect to my EC2 instance in the next step.

### Key pairs

A key pair is like a lock and a key for our EC2 instance. It's used for
authentication, i.e., for us to securely get access to the EC2 instance. The key
pair is two halves, i.e., a public key and a private key, which should be matched.

Once I set up my key pair, AWS automatically downloaded a file called
nextwork-keypair.pem. This file is a private key certificate, i.e., the first half of the
key pair that will need to access EC2 instance


#### NextWork Student NextWork.org

## Set up VSCode

VSCode is an IDE (Integrated Development Environment). It's software for
editing and creating code.

I installed VSCode to use to connect with the EC2 instance and then create and
edit web app files on that EC2 instance.


#### NextWork Student NextWork.org

## My first terminal commands

A terminal is a space for us to communicate with the system using text-based
commands to control and create action with our computer/server. Using
terminal eliminates clicks and drags to perform tasks. The first command I ran
for this project is "cd"

I also updated my private key's permissions by "icacls nextwork-keypair.pem.""
/reset icacls "nextwork-keypair.pem" /grant:r "%USERNAME%:R" icacls
"nextwork-keypair.pem" /inheritance:r"


#### NextWork Student NextWork.org

## SSH connection to EC2

## instance

To connect to my EC2 instance, I ran the command ssh -i [path where
The nextwork-keypair.pem file is located ec 2 - user@[Public IP DNS of EC 2
instance]. Ensure that the keypair.pem has read permission enabled.

### This command required an IPv4 address.

A server's IPv4 DNS is its public address. Computers/servers connected to the
The internet can use public IPv4 DNS to find and locate another server.


#### NextWork Student NextWork.org

## Maven & Java

One tool/package manager for the software development process is Apache.
Maven. When it comes to adding packages to our application, Maven is
incredibly useful.

Because Maven is so useful for integrating packages into our application—that
is, any software tools—and packaging our app after it has been developed, it is
necessary for this project. It requires compiling and packaging code.

Numerous applications are made using a programming language called Java.
We've downloaded Amazon Corretto 8, which is a specific version of Java that
is managed by Amazon (AWS).

Because we intend to create a Java web application, we must install Java.
Before we can execute any Java commands, Java is necessary for this project.


#### NextWork Student NextWork.org

## Create the Application

'I generated a Java web app using the command using the Maven command.
"mvn archetype:generate," which creates a simple web application using
Maven's archetype template.

I set up the Remote-SSH extension so that I could connect VSCode to our EC2
instance directly. Doing this means we can later use VSCode as an IDE for Java.
web app files in our EC2 instance. This makes editing our web app much
simpler/more efficient.

The host name (i.e., the IPV4 DNS of our EC2 instance), the location of our
private key on our local computer, and the SSH host's user that we are
connecting to are configuration details needed to establish a remote
connection.


#### NextWork Student NextWork.org

## Create the Application

Using VSCode's file explorer, I was able to quickly view a file tree of all the
subfolders and files that comprise the nextwork-web-project folder for our
Java web application by using VSCode's file explorer.

Two of the project folders created by Maven are src and webapp. While
webapp is a subfolder of src that concentrates on what the user would see, src
contains all of the web application's source code that determines the look and
feel of the web app.


#### NextWork Student NextWork.org

## Using Remote - SSH

index.jsp is a file within the webapp folder, and it defines the look of a Java web
app.

Even though index.jsp is stored remotely in my EC2 instance, I used VSCode to
edit it because I had established a remote SSH connection between the
instance and VSCode. We can use VSCode as a local IDE for our instance.


### NextWork.org

# Everyone

# should be in a

# job they love.

## Check out nextwork.org for

## More projects
