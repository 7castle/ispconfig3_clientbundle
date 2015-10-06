# ispconfig3_clientbundle
Small web form that creates clients, domains and all associated accounts (ftp, db, mailboxes) based on default settings. In other words, it makes it easy for an admin to create all the accounts related to a webhosting solution (FTP accounts, databases, database users, mail domains, mailboxes etc)

It uses the SOAP API provided by the ISPconfig3 team. It has mostly been a copy'n'paste'modify from the examples provided in the documentation.


# How to use
- Replace your credentials and URL in the soap_config.php file
- Open the inputBundleVars.html file in your browser
- Fill in the form
- Check your ISPConfig3 dashboard for the changes

# References
- https://www.howtoforge.com/how-to-create-remote-api-scripts-for-ispconfig-3
