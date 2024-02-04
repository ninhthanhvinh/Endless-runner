# Address Book and Invitation sent via mail implemented
## AddressBook
* Can access by pressing a button.
* Display a listview of contact inform that contains first name and last name. If a contact have atleast an email, display a button to send invitation email to this.
* The data of contacts only can be read in the callback, if I try to read it outside it returns null, so that I guess it is caused because all function is not synchronous.
## Invitation sending via mail
* Click the button displayed next to a contact to send an email to this contact.
* Then send the email created to complete invitation mail.
* I don't know if the mail composer can send email automatically, then I try to get more information about this by finding documents and try using essential kit's demo. 
## Fixing UI
* Make the UI canvas fitting many sizes of screen.
* Make button and title clear and easy to interact with.
