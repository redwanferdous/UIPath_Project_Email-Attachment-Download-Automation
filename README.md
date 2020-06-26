# UIPath_Project_Email-Attachment-Download-Automation
This is a UI Path based workflow, which will search mail inbox for certain email with certain specifieed subject line and then download the attachment(s) in specified folder in local machine upon execution.

Details:

"Email Attachment Download Automation" is a UI Path Designed file which is executeable. 
--------------------------------------------------------------------------------------
To Run the File:

- Extract the file and save this in location, preferably in UIPath folder of your machine
- Open UI Path Studio
- Show the downloaded file path
- Select on 'Project' file 
- Click on 'main.xaml' under Project Tab
- Save in your local machine
- Run/Debug
-------------------------------------------------------------------------------------
Before you start:

- Click on the  'Variable' in the canvas file
- Put your "Email ID" in 'email'-variable [preferably Gmail ID]
- Put your "Password of that Email ID in 'password'-variable
- Show the location/ file path of the folder, where the attachment will be downloaded and saved.

-------------------------------------------------------------------------------------
If you run this file:

- It will go to Gmail.com and login using your email ID and password. 
- It is suggested that, you don't use 2-factor authentication /any authentication other than password in this case
- It will search for first '30' email in your inbox with subject line 'Attachment'.
- If it finds any email containing the subject 'Attachmnet', it will download the attachment in that email.
- The attachment will be saved in the showed path. [You can change it]
- If there is no attachment, it won't download.

-------------------------------------------------------------------------------------
Special Note:

- If you want to increase the search number of inbox, i.e. you want to search 100 email with the 'Attachment' subject line 
instead of '30', you have to go the rght-hand side 'Properties' of imap and select 100 instead of 30 in the mail section.


- You can change the search criteria. I.E. you can search for anything in subject line instead of 'Attachment'.
What ever you want to set, simply write it exactly inside the inverted comma.

- If there is more than attachment with the same file name, it wwill be replaced each time.

---------------------------------------------------------------------------------------

For any query, or confusion- you can mail me: redwan.contact@gmail.com

The Canvas was developed in UI Path Studio, Version: 2020.4.1


Developed By:

Redwan Ferdous Farhan
Dhaka, bangladesh
June 2nd, 2020
