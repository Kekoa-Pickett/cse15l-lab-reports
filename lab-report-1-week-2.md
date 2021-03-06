## Installing VScode
For this step, I went on the VS code app. Once I downloaded it for the MAC, I opened it and created a workspace. To download, use [this link](https://code.visualstudio.com/).
<img width="1023" alt="Screen Shot 2022-04-07 at 8 00 46 PM" src="https://user-images.githubusercontent.com/103221420/162355096-22c141e5-5b1b-47b2-9365-964414c856ba.png">

## Remotely Connecting
To connect remotely, I had to create my own account and password. I used my school email and it worked fine but had to change it to the CS one.
![image](https://user-images.githubusercontent.com/103221420/162629013-5c8701e4-fd10-47a5-826d-e3e2ab427edd.png)

## Trying Some Commands
I tried the ```ls``` and ```cat``` commands on my client. I can’t copy or access anything because the permission is denied. To search for files, use ```ls -a``` to access hidden files. 
![image](https://user-images.githubusercontent.com/103221420/162629348-8910c2de-e874-4b04-8a74-c1e1272cdf3b.png)

## Moving Files with scp
This took me 4:06, just because I tried to log do scp after logging into ssh which gave me a message asking to permanently add a host key for IP. It will get faster the more times you do it.
![image](https://user-images.githubusercontent.com/103221420/162629639-0602edb6-8126-4dc6-a68a-436ba7693f50.png)

## Setting an SSH Key
Create a key using both the server and client. A key is a lot faster than typing my password, I can move files a lot faster now.
![image](https://user-images.githubusercontent.com/103221420/162629818-df70bdb3-c75b-4dea-9988-22033bdb5742.png)

## Optimizing Remote Running
Use scp to copy the file and make sure to add ":~/" to the end. Then, use up arrows if you already have written it or log in to ssh and use quotation marks and semicolons to store and run the file at once. This way, you don't have to wait for each command to happen before writing the next one. It also takes up a lot less space from a visual perspective when you look at the terminal.
<img width="1081" alt="Screen Shot 2022-04-18 at 3 37 32 PM" src="https://user-images.githubusercontent.com/103221420/163888467-2ac4e73c-a5df-44a7-9105-6e91633ff049.png">

