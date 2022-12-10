# OSIF

![1583987266101-01](https://user-images.githubusercontent.com/106522935/206839341-4dfe46fd-d09a-4452-afc5-a2b2d68a7d69.jpeg)


# Introduction 

OSIF is an accurate Facebook account information gathering tool. It can gather all sensitive information easily from facebook by dumping the target account even though the target converts all its privacy to (only me), Sensitive information about residence, date of birth, occupation, phone number and email address are easily access from this tool.

# Installation

     $ git clone https://github.com/ciku370/OSIF
     
![1583987195541](https://user-images.githubusercontent.com/106522935/206838285-29183c67-70b9-45a8-8b63-cffbd9e9a581.jpeg)

     $ ls
     
![1583987215680-01](https://user-images.githubusercontent.com/106522935/206838423-8d3b1106-92e0-455b-9b27-b2046aac3023.jpeg)

     $ cd OSIF

![1583987215680-02](https://user-images.githubusercontent.com/106522935/206838453-dea0abfd-f49d-47c0-81b0-cc18e468c9bd.jpeg)

Now, we must fulfil some requirements, for that hit the following command. Because pip3 is not installed by default.

     $ pip3 install -r requirements.txt

![1583987234537](https://user-images.githubusercontent.com/106522935/206838645-0d64d729-bd2a-4cc4-982a-94b11e9ef320.jpeg)

     $ ls
     $ chmod +x osif.py

![1583987254043](https://user-images.githubusercontent.com/106522935/206839234-d0240ab7-99f5-4c3f-b0f5-d4ad9be96fd5.jpeg)

Note: “chmod +x” command on a file (osif.py) only means, that you will make it executable.After the command,you can see the osif.py have changed colour to green.It means it Is executabe. And then,

     $ python2 osif.py

![1583987266101-01](https://user-images.githubusercontent.com/106522935/206839321-0df553bc-41e5-4f2f-a01a-1b78497f3346.jpeg)

# Exploitation

     D3b2y >> help

![1583987285444](https://user-images.githubusercontent.com/106522935/206839824-7e489fbf-0bce-4d53-a68f-777c06b079a4.jpeg)

Note: “help” command helps to list what are all the exploits can be done in OSIF.
*make sure your Facebook do not have the 2-way authentication * And then,

Enter the command token 

     D3b2y >> token

![1583987305198](https://user-images.githubusercontent.com/106522935/206839884-a4419bf8-0a7d-4829-9834-c3dde8c9e129.jpeg)

After that enter your Facebook Username and Password. It establish the connection with your Profile and generate the connection token, if the username and password are correct.

![1583987369153](https://user-images.githubusercontent.com/106522935/206840172-2da543a0-a5bc-42c3-a75a-54cd2fc7a481.jpeg)

The token will be successfully generate the access token and it will stored in the cookie/token.log file.

![1583987389493](https://user-images.githubusercontent.com/106522935/206840251-05d462e4-71f3-4020-bd86-0232a93ff2e5.jpeg)

     $ python2 osif.py

*to get back to the OSIF framework*

![1583987266101-01](https://user-images.githubusercontent.com/106522935/206840327-d8861fd0-41df-45be-a5d5-70720f16d1fd.jpeg)

Note:Now it will show the account name which you have logged in earlier.It means that we are on the victim's account and we are ready to exploit.

     $ help

![1583987432831 (1)](https://user-images.githubusercontent.com/106522935/206840358-f7a681d3-7048-4831-a410-2ccb2ebb07bd.jpeg)

     D3b2y >> dump_phone

Note: “dump_phone” command fetches all the contact number of the victim’s Facebook friends.

![1583987453297](https://user-images.githubusercontent.com/106522935/206840408-85fa1cd3-f47b-462b-a782-a1bcdaa05c77.jpeg)



