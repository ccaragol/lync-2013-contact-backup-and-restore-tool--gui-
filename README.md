Lync 2013 Contact Backup and Restore Tool (GUI)
===============================================

            

 I developed this tool simply because I realized when attempting a Lync 2013 contact restore that it's difficult to tell which backup to use.  This is especially true when the user
 can't quite remember when or how the contacts were removed.  I also realized that for some companies, not all of the staff is PowerShell savvy and enabling them to make easy backups and restores through a GUI would prove to be quite helpful.  What
 I've done is written a PowerShell tool that allows for easy backups and restores of contact data, and also allows you to review the contents of your backup before you merge the data into your production system.  To run the tool, simply download the script
 from the TechNet Gallery and run it from a Lync server.  One item to note before we start, the PowerShell commands this tool uses do not work with the unified contact store (UCS).  What this means is you're fine with this tool if you're running Exchange
 2010 or prior, or if you're running Exchange 2013 but haven't enabled the unified contact store to move your contacts out of Lync and exclusively into Exchange.


 


![Image](https://github.com/ccaragol/lync-2013-contact-backup-and-restore-tool-(gui)/raw/master/step4small.jpg)



Thank you!


 


        
    
