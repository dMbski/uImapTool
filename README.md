# uImapTool 
Very simply IMAP data (emails) manipulation program, directly on server.
On first stage of development (super_pre_alpha), USE only on OWN Risk.

<img src="https://github.com/dMbski/uImapTool/raw/master/screens/Schowek01.jpg" /><img src="https://github.com/dMbski/uImapTool/raw/master/screens/Schowek02.jpg" />

Uses:
- Ararat Synapse, www.ararat.cz/synapse/
- The OpenSSL Toolkit
- Icons by www.icons8.com

Made with Lazarus (Free Pascal RAD IDE) www.lazarus-ide.org

### How to use:

This program bases on IMAP _profiles list_. It is list with imap data needed for login.
All profiles in list can be _validated_ by Check button. 
If profile data is correct, its size is entered in the last column (usefuly to check quotas).

The list can be encrypted. Just use Password button and set password (min. 8 chars). Dont forget to save list!
Default location for loading list is program directory.
When list is loaded the program will ask for password (if it is not there, leave the field blank).

_Program is in early stage, please save unencrypted list first, then try set your password and save again to another file. Check encryption, by loading encypted file. If enc. file is loaded properly, then delete unencrypted file. _

Unencrypted file is in CSV format and can be imported (loaded). To check its format save unencrypted file.

1. Load, create profiles.
2. Load profile data into imap worker (blue or red). Button __Load as ...__
- Program will load folder list. Changing folder will load messeges' data into table (wait to end this).
Select mails to copy/move/delete. Program will _not auto update message list_ (long operation).

3. Load another profile data into second imap worker.
4. Select and Copy/move emails between these two.

