# Creating-a-Windows-Desktop-VM

Virtual machines are highly valuable when it comes to developing skills in tech. An individual is essentially given the ability to build and tear apart any software they would like without having to suffer any repercussions. However, with all of this said, simply having virtual machine software on your computer is one thing; using it to sharpen and hone one's skills is a completely other matter. To begin, you must first understand how to create your own personal boxes on your VM software. In this case I am using VirtualBox and the box I am creating is a Windows desktop. If you are curious on how to download the VirtualBox software on your PC, I have made an article you are able to reference titled “Downloading VM Software”. In this article, I  will be walking through the process of downloading and creating a Windows vm in VirtualBox.

Something important to understand is that when downloading software to load into a VM, one of the easiest methods is to convert them into a .iso media file. Knowing this and the fact that I have Windows 10 on my PC, I made the decision to download a windows 10 .iso file. Therefore, if I am ever curious about trying something new on my personal operating system, I have the opportunity to simulate it in a sandbox environment. 

I first began with searching the term “windows 10 iso”. I was then directed to a google webpage with the “Download Windows 10 Disc Image (ISO File)” link at the very top. This was the link I was looking for.


![image](https://github.com/user-attachments/assets/a1e37bda-4398-47fc-b5a1-43890f3ed65a)


![image](https://github.com/user-attachments/assets/b0a4b14d-3ae9-4577-881c-a4b9ae5bdffc)


Being directed to the following page, I then was required to download a license for installing Windows 10 onto my machine. All this required was clicking the “Download Now” option on the lower half of the screen. This download took little to no time for my machine so I was then able to immediately navigate to my downloads folder and open the .exe file. I then clicked on “yes” to allow any changes to be made as a result of downloading the software.

Following, I was then prompted with a license agreement which I read then accepted.


![image](https://github.com/user-attachments/assets/a3c78d02-ae6f-42e4-a511-c7fca54d8982)


Now I was directed to a more important part. I then had to specify that the software needed to be downloaded to the computer as a media file and not configured to my current OS. So I selected the second option to “create installation media” and clicked the “next” option on the bottom of the window.


![image](https://github.com/user-attachments/assets/6bda11dc-f985-42c9-832d-7012b4d5e186)


Since I did know that my computer could handle running a 64 bit machine from checking in the settings, I decided to continue with the default choice I was given by microsoft and selected “next” again.


![image](https://github.com/user-attachments/assets/a07236dd-e3c3-4251-b38f-ebc6e416ef1f)


I then needed to specify even more that the data needed to be formatted in an ISO file. Following hitting the “next” button, I was required to decide on where in my file system the .iso file was going to be stored. For those who are following along in this guide step by step, be sure to keep this file somewhere it can be easily found.


![image](https://github.com/user-attachments/assets/4ddc4212-13de-43de-9624-7813be9db936)


Once the download completed, I selected the “finish” option and opened VirtualBox on my computer. I found the “new” option under the “machine” tab on the top left of the window. This allowed me to create a new box using our .iso file.


![image](https://github.com/user-attachments/assets/7c4f1999-ba06-4d25-975a-b85c74631da8)


I was required to name the VM, pick a folder on my PC to store the data, and select from my files which ISO image I wanted to load into the VM. Also I made sure that “Microsoft Windows” was the type of OS chosen and the version was correct for the type of box I was interested in creating. After filling in this information I clicked the “next” option. 


![image](https://github.com/user-attachments/assets/4a74d844-d07c-416b-8c50-3b429036b48b)


I did need to alter the hostname of the machine in the following window. The VirtualBox software does not like special characters such as spaces, so I decided to replace them with dash marks. All was good to go once I only saw check marks and no alert symbols.


![image](https://github.com/user-attachments/assets/185087e1-0303-44cf-9f7a-46fcfa42957e)


I then filled in the rest of the information on the following prompted windows until I was brought to the summary. All of that information will vary based on your PC capabilities so I will not go into everything that I selected. However, almost anyone can spin up a VM on their machine depending on what they want to do. VirtualBox will help guide your configuration as you go along. Just be sure not to move any gauges into the red when configuring your VM. Worst case scenario, your VM does not operate correctly or to your liking and you need to create a new one with lowered settings. This is all a part of the learning process which is important!
Once reaching your summary window, double check over all of your configurations and file locations to make sure everything is correct and then select “finish”. 

After leaving the summary window I then was indicated that my VM was now in the left column of the page and already running.


![image](https://github.com/user-attachments/assets/08d2c1d3-e27c-4fab-957e-c434cb7e715f)


Before being able to start using my VM I was required to do a couple more steps. First was that I needed to shut down my machine and navigate to the settings option for my VM. Under “system” on the left column there was a “floppy” option that needed to be disabled under my boot order. 


![image](https://github.com/user-attachments/assets/7d9eb6e4-24b8-49a5-891c-8ef958654105)

Then, I needed to go to the “general” tab on the left and find the location of my VM files under the “advanced” section. 


![image](https://github.com/user-attachments/assets/87f00748-1a1e-40f1-8603-ff1f1c73783a)


I then found the location of files within my PC file manager and found a long image file that needed to be deleted from the folder.


![image](https://github.com/user-attachments/assets/72b6d796-fead-47dc-89c2-749f77d2acd5)


Finally, I was happy to see that all was up and running properly after restarting my Windows VM in VirtualBox. Now the real fun was able to begin!

![image](https://github.com/user-attachments/assets/8f4396b3-ae32-43c6-b472-dd5cdf1da7f0)



Thank you to everyone who took the time to read this guide on creating a windows VM in VirtualBox. I hope this provides at least some help to the individual who wants to make their first steps with VM technology. Also, if you are curious on any other topics, feel free to see what other articles and projects I discuss that may peak your interests!
