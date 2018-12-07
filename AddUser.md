# Adding a User Account
On the User management page of ownCloud Web UI, you can add a new user account.
User accounts have the following properties:

Property Name              |	      Description
---------------------------|---------------------------------------------------------
Login Name (Username)      |	The unique ID of an ownCloud user that cannot be changed.
Full Name |	The display name of the user that appears on file shares, the ownCloud Web interface, and emails. Administrators and users can change the Full Name any whenever needed. If the Full Name is not set, then a default name with the format, login name.ownCloud domain is assigned.
Password |	The administrator sets the first password for the user. Both the user and the administrator can change the password later.
Groups |	Group memberships are assigned to users. By default, new users are not assigned to any groups.
Group Admin |	Group admins are granted administrative privileges on specific groups, and can add and remove users from their groups.
Quota	| The maximum disk space assigned to each user. Any user that exceeds the quota cannot upload or sync data. You have the option to include external storage in user quotas.
## How to Add a New User
To create a user account, select **users** from the **users** drop down box and click the **Create** button as shown below.
![Create User](/AddNewUser.png)
 
You need to enter new Login Name of the user and the initial Password. You can assign a group membership by selecting **Add Group** option.
Login names can contain: alphabets (a-z and A-Z), numbers (0-9), dashes (-), underscores (_), periods (.) and at signs (@). After creating the user, you can fill in their Full Name if the name is different from the login name, or leave it for the user to complete.
For more information, see [User Management in ownCloud Administration Guide](https://doc.owncloud.com/server/10.0/admin_manual/configuration/user/user_configuration.html).
 
# Connecting to the ownCloud Server Using the Desktop Client
As a User, you can connect and synchronize with the ownCloud server by using the ownCloud Desktop Synchronization client. 
The ownCloud desktop client enables you to:
*	Specify one or more directories on your computer that you want to synchronize to the ownCloud server.
*	Always have the latest files synchronized, wherever they are located.
Your files are always automatically synchronized between your ownCloud server and local PC. There are clients for Linux, macOS, and Microsoft Windows.
You can use MSI installer to install ownCloud desktop client. This client provides several features that can be installed or removed individually. which you can also control through command-line. If you are automating the installation, then run the following command:

```msiexec /passive /i ownCloud-x.y.z.msi```

If you just want to install ownCloud Desktop Synchronization Client on your local system, you can simply launch the `.msi` file and configure it in the wizard that pops up. For more information, see [ownCloud Client manual](https://doc.owncloud.org/desktop/latest/).
# Connecting to the ownCloud Server Using the Mobile Client
Using web interface to access files on ownCloud is easy and convenient as you can use any Web browser on any operating system without installing special client software. However, the ownCloud Android app offers some advantages over the Web interface:
*	A simplified interface that fits nicely on a tablet or smartphone
*	Automatic synchronization of your files
*	Share files with other ownCloud users and groups, and create multiple public share links
*	Upload of photos and videos recorded on your Android device
*	Easily add files from your device to ownCloud
*	Two-factor authentication

You can get ownCloud Android app by logging into your ownCloud server from your Android device using a Web browser such as Chrome, Firefox, or Dolphin. For more information see [ownCloud Android App Manual](https://doc.owncloud.org/android/).
