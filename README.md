# PhoneNoteBook

A Python Script that manages an agenda where you can put some your information, modify them, remove them or search them
<hr>
USAGE:

python MyPhoneNoteBook.py [options] [params] <br> <br>

<em><strong> Options and params: </strong></em><br>

1 - To add a new contact: -a|--add [surname] [name] [phone_number] [description(optional)] <br>

2 - To modify a contact: <br>

&nbsp;&nbsp; To modify a phone number: -m|--mod t [surname] [name] [new_phone_number] <br>

&nbsp;&nbsp; To modify a description: -m|--mod c [surname] [name] [new_description] <br>

&nbsp;&nbsp; To modify all the informations -> -m|--mod b [surname] [name] [new_phone_number] [new_description] <br>

3 - To remove a contact (if there are more of one contact with this surname, you should put also the name): -r|--rem -r [surname] <br>

4 - To search a contact: -s|--search -s surname [name]
