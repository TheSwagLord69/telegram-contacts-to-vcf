# Convert Telegram contacts to a .vcf

Converts the contacts exported from Telegram Web to a .vcf format for your phone to import the contacts.

## Prerequisites

Python 3

## Usage

python telegram_export_contact_list_to_vcf.py [path of contacts.html]
E.g., python telegram_export_contact_list_to_vcf.py D:\Users\User1\Downloads\Telegram Desktop\DataExport_2022-01-17\lists\contacts.html

### How to export contacts from Telegram

Using Telegram Desktop, <br>
Settings > Advanced > Export Telegram Data > Check only "Contacts list"<br>
For more details, view https[:]//www[.]quora[.]com/How-can-I-export-telegram-contacts

### Finding contacts.html

After exporting, navigate to "Telegram Desktop\DataExport_YYYY_MM_DD\lists"
