# PDF-protector
Protect your PDF files with Password

We will use python library PyPDF2 to set password to pdf file.

To install PyPDF2:

sudo pip install pypdf2
1
sudo pip install pypdf2
We are using encrypt function of PyPDF2.

encrypt(user_password, owner_password=None, use_128bit=True)

user_password  – The “user password” allows opening and reading the PDF file with the restrictions .
owner_password – The “owner password”  have no restrictions. By default, the owner password is the same as the user password.
use_128bit  – Decides which encryption to use128bit or 40bit.
