# Alfred2 - LDAP Search workflow

This is a quick workflow that do ldap search based on keyword.

The killing info here is the ``ldapsearch`` command line that let you request your company ldap - right from terminal. You just need to get started by analysing the command within this workflow and customise it the way you want to process it.

As this is my first Alfred Workflow, chances are very hight that this could be optimised and performed in a better way. So feel free to propose improvments or variants.

If you want to use this, you will have to change some param to fit with your own LDAP settings.
This include ldap server address, domain component (dc=…, dc=..) and the domain for people email address in regex parsing.

To do those mandatory local adaptations, edit the python script in a more readable editor and check for your own settings.

Because there is no authentication to LDAP here, you can only grab email, tel and name. 

It might be possible to have more propertises (like person picture, mobile number, etc.), but this would depend of your ldap policy I guess.

You might want to customise the properties you ask to ldap and modify a bit the parsing part. This ldap result parsing made here fit my own company ldap result. It might change a bit for yours.


Don’t hesitate to share you improvements or comments.
