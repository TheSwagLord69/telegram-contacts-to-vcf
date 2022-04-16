#Telegram contacts to .vcf

A simple script that converts the contacts exported from Telegram Web and creates a .vcf for your phone to import the contacts. <br>

## Prerequisites

Python 3  <br>

## Usage

python telegram_export_contact_list_to_vcf.py [path of contacts.html] <br>
E.g., python telegram_export_contact_list_to_vcf.py D:\Users\User1\Downloads\Telegram Desktop\DataExport_2022-01-17\lists\contacts.html <br>

### How to export contacts from Telegram

Download Telegram Desktop and log in. <br>
Using Telegram Desktop, <br>
Settings > Advanced > Export Telegram Data > Check only "Contacts list" <br>
For more details, view https[:]//www[.]quora[.]com/How-can-I-export-telegram-contacts <br>

### Finding contacts.html

After exporting, navigate to "Telegram Desktop\DataExport_YYYY_MM_DD\lists" <br>
contacts.html should be in this directory. <br>
