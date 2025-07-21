# PhoneNoteBook

A Python Script that manages an agenda where you can put some your information, modify them, remove them or search them
<hr>
USAGE:
python MyPhoneNoteBook.py [options] [params]

1 - To add a new contact: python MyPhoneNoteBook.py -a|--add [surname] [name] [phone_number] [description(optional)] <br>
2 - To modify a contact: <br>
	 To modify a phone number: python MyPhoneNoteBook.py -m|--mod t [surname] [name] [new_phone_number] <br>
	 To modify a description: python MyPhoneNoteBook.py -m|--mod c [surname] [name] [new_description] <br>
	 To modify all the informations -> python MyPhoneNoteBook.py -m|--mod b [surname] [name] [new_phone_number] [new_description] <br>
3 - To remove a contact (if there are more of one contact with this surname, you should put also the name): python MyPhoneNoteBook.py -r|--rem -r [surname] <br>
4 - To search a contact: python MyPhoneNoteBook.py -s|--search -s surname [name]
