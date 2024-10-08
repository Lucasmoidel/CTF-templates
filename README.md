# CTF-templates
Download the template CTF virtual machine then click Import.
![Screenshot_20241005_192206](https://github.com/user-attachments/assets/2c0b24d0-9789-4c54-9518-24835d6d2fad)

Locate and open the ova file then click on the settings dropdown.
![Screenshot_20241005_192243](https://github.com/user-attachments/assets/63444b5d-98d9-4376-bc82-94b710b76068)

Rename the virtual machine to “(your name) CTF (CTF number)” as shown below.
![Screenshot_20241005_193505](https://github.com/user-attachments/assets/d0c43bd2-452f-4914-b989-7185fb1547ce)

Make sure to uncheck import hard drives as VDI.
![Screenshot_20241005_193511](https://github.com/user-attachments/assets/15b9c589-3ff8-42fd-908c-f1702bf3aef2)

Then click finish and wait for it to import.

![Screenshot_20241005_193515](https://github.com/user-attachments/assets/04801641-a793-4d75-8ada-0094343621ea)

Now that you have imported the template it is time to make your CTF. Run your virtual machine by clicking on the start button.
![Screenshot_20241005_230051](https://github.com/user-attachments/assets/595b7db5-12da-4fc8-b78f-fba6c4de4cf3)

Once the virtual machine finishes booting you will see the login screen. You need to log in as the root user with the password “password”. This is a TEMPORARY password DO NOT leave this as the password or others will be able to log into the root user account that has privileges over the entire system.

![Screenshot_20241005_230138](https://github.com/user-attachments/assets/49f52653-c3eb-49ba-a479-49684c1ac112)

The first step is changing the [hostname](https://en.wikipedia.org/wiki/Hostname). Type in “nano /etc/hostname”, this will open a text file in the [nano](https://en.wikipedia.org/wiki/GNU_nano) text editor. Delete the text that is there and replace it with “(your name)-CTF-(CTF number)” then save it by pressing ctrl+x then y, then enter.

![Screenshot_20241005_230212](https://github.com/user-attachments/assets/b2c63252-ed44-4cb4-86ec-13d5936c9c15)
![Screenshot_20241005_232636](https://github.com/user-attachments/assets/2e8139ab-bf1d-4cb3-97ec-b7517f012bf5)

Next change the password with the ”passwd” command. It is important to write this down somewhere so you will not lose it. You cannot see what you are typing for security reasons.

![Screenshot_20241005_230249](https://github.com/user-attachments/assets/7395567e-9bc6-44eb-8ba3-3216313b851c)

There is another user called player that the player will SSH into. I recommend making your CTF in the root user’s home directory and copying files to the player’s home directory when done.

![Screenshot_20241005_233050](https://github.com/user-attachments/assets/9736da97-2cc8-4ebd-b9b8-23b32e7e49d9)

Once you have completed your CTF make sure to shut down the system then click on File > Tools> Virtual Media Manager.
![Screenshot_20241005_194107](https://github.com/user-attachments/assets/4a44c991-390a-4c38-b0f6-946bdb9deb88)

Click on “CTF template-disk001.vmdk” then click on Move at the top. Save the file as “(your name) CTF (CTF number).vmdk”. Then right-click on the file and go to properties
![Screenshot_20241005_200530](https://github.com/user-attachments/assets/078be427-8709-4429-b745-98d7f3a409f8)

Find where the file is located and [email](mailto:lm7204@pleasantonusd.net) it to me along with the password
![Screenshot_20241005_193746](https://github.com/user-attachments/assets/02e9dd54-3c99-4065-abd9-a15c40302ab7)

If you have any questions email me at [lm7204@pleasantonusd.net](mailto:lm7204@pleasantonusd.net)
