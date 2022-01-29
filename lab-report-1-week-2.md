# Welcome to Lab Report

*Today I will present then step-by-step instructions on how to log into a course-specific account on `ieng6`*.
>Step One - Installing VSCode

*Go to the Visual Studio Code website [VSCode](https://code.visualstudio.com/), and follow the instructions to download and install it on your computer. There are versions for all the major operating systems, like OSX (for Macs) and Windows (for PCs). I personally own a Mac, so I did not follow the Windows installation guide.
Upon completion of the step, this is the interface you should be able to see:*

![Image](VSCode.png)

>Step Two - Remotely Connecting

*In order to get connected you need to know your personalized encryption of your account. For you to find that information you should follow the [link](https://sdacs.ucsd.edu/~icc/index.php). Once you log in, make sure to initialize the reset of the password - **might take some time**.
You have to plug in your personalized letters instead of **zzz** as follows:*

![Image](SSH.png)
![Image](SSHLogged.png)

*Congrats!*
>Step Three - Trying Some Commands

*For anyone reading my instructions please be mindful of the fact that I go by Sasha as I am Russian, so my computer is Sasha's. Those are my screenshots :) 
The following screenshot presents some of commands that can be tried out by anyone desiring:*
![Image](Commands.png)

>Step Four - Moving Files with scp

*It is important to be able to go back and fourth between the client (your comoputer) and the remote one.
In order to familirize ourselves with the command that does just that we will first create a file **New.java**:*
![Image](NewFile.png)

*Now I am going to copy the file to the remote server using command scp:*
![Image](Copied.png)

*Now if we enter the remote server using the old procedure and ask it to list everything that is n there, we will see
the New.java there:*

![Image](OnRemote.png)

>Step Five - Setting SSH Key

*Plugging in the password all the time can get tiring, so we can create a SSH key that would be our authentificator.*

![Image](Connecting.png)

*We can make sure we are connected:*

![Image](checked.png)


> Step Six - Optimization

*We see the New.java on remote server and the changes are presented to us. Yay!*

![Image](Final.png)


How to make remote running more pleasant? Just take a look at the screenshot.

<img width="767" alt="Screen Shot 2022-01-28 at 15 59 06" src="https://user-images.githubusercontent.com/97698957/151637294-92bd6296-479b-49fa-867c-f4cb27f87086.png">
