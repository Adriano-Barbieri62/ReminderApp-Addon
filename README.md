# ReminderApp (Reminder) - User manual

With ReminderApp (Reminder), no more forgetting!    
Rest assured, this program is there to remind you of everything that is important thanks to reminders such as (eg: take your medication, don't forget an appointment or someone's visit, with the baby-minder, domestic help, nurse, etc.).    
Even birthday reminders!    
We've all experienced this embarrassing moment at least once in our lives: forgetting a loved one's birthday! It must be said that it is not always easy to remember the birthday dates of all the people you are used to knowing (especially when you come from a large family or are part of a large group of friends).    
You enter the birthday dates of the whole family and the program will remind you of them every year with an alarm, including reminders of a anniversariy!    
This program also contains an address book and much more to discover!    

To learn more and configure this program Please read this documentation in its entirety. Thanks.    

# User Guide

* Author: [Adriano Barbieri](mailto:adrianobarb@yahoo.it)
* Last modified: January 2025

## Table of contents

* [1.\ Introduction](#toc1)
* [2.\ Setting up the program](#toc2)
* [3.\ The menus](#toc3)
* [4.\ Additional information for the main window for the option "Reminder for the selected day:"](#toc4)
* [5.\ How does the Address book work?](#toc5)


---


# 1.\ Introduction <a name="toc1"></a>
ReminderApp is a combination of agenda and an address book for NVDA.    
This program is very intuitive and does not require much explanation, however I will give you some guidelines to follow.    

# 2.\ Setting up the program <a name="toc2"></a>
The addon contains the following elements:    

* The "Sounds" folder which contains the alarm sound files, you can add them directly to this folder as long as they are in "wav" format, and their duration is less than 2 seconds, ReminderApp will automatically load the names and sort them when will enter in the "Set notifications" configuration option, which means that if you add alarms, the number of alarms you set may change and you will have to reset it in the Settings menu Alt+i submenu and then in the "Set notifications" dialog in the drop-down list called: Use alarm: followed by the name of the alarm.    
There is also a "Samples" folder inside the "Sounds" folder, these sounds are used by the program.    

# 3.\ The menus <a name="toc3"></a>
In the main window of the program at startup we will find the following five menus with their respective commands.    

# File Menu Submenu Alt+ f

In this first menu we will have the following options:    

* Export your address book contacts... Ctrl+Shift+E    
Press Enter, a dialog box appears as name:    
`Export contacts`    
Select the location and export name of your list, in the edit field:    
`File name`    
Then indicating txt or json in the document type.    
`Type :  Text files (*.txt)`    
Down arrow to find:    
`JSON files (*.json)`    
Finally save your file by pressing the button:    
`Save`    
If everything went well, the following message will appear:    
`Note! Contacts exported successfully!`    
* Import contacts into your address book... Ctrl+Shift+i    
Press Enter, a dialog box appears as name:    
`Select a file to import`    
`File name`    
Then indicating txt or json in the document type.    
`File Types: JSON Files (*.json)`    
Down arrow to find:    
File types: Text files (*.txt)    
Select the previously exported txt or json file, then open it by pressing the button:    
`Open`    
If everything went well, the following message will appear:    
`Note! Import completed successfully!`    
Press the `OK` button, A new dialog box appears with the name:    
`Choose how to proceed`    
`By choosing Yes, the contacts will be overwritten.`    
`By choosing No, they will only be added to existing ones.`    
Press either the Yes or No button depending on your choice.    
FOR YOUR INFORMATION    
`JSON files in the case of this program are structured as a list of data, for example: ["...", "...", "..."] and are more convenient for the program to manage, while text files they are structured with a new line marker, for example line\nline\nline etc which are more human readable`.    
* Close Alt+f4    
This option simply closes the main ReminderApp window and you can reopen it using the combination NVDA+Shift+F2, or the combination you set.    

# Edit Menu Submenu Alt+ e

In this second menu we will have the following options:    

* Add reminder... Ctrl+n    
* Edit reminder... F2    
* Move reminder... Ctrl+F2    
* Delete reminder... Del    
* Additional reminder notes (submenu) with 3 items:    
* Add... Ctrl+Shift+1    
* Edit Ctrl+Shift+2    
* Delete Ctrl+Shift+3    
If you add a note to a reminder, it will be saved in ReminderApp_config /ReminderApp_notes folder.    
Notes have a unique number in the file name, e.g. "Notes_xxxx.txt", the program is therefore able to find and manage them.    
Note: In the dialog, when adding an Anniversary or Birthday, you can also select a tune and play/stop it via a combo box and button.    
The melodies are stored in the Sounds, Samples, Melodies folder and are in .wav format.    
You can add more as long as they are of the same format and of short duration.    
If there are multiple anniversaries/birthdays on the same day, these will be grouped into a single notification, therefore the first melody on the list will be used.    
Continuing with the Edit menu:    
* Delete past appointments... Ctrl+Shift+a    
* Eliminate past medicines... Ctrl+Shift+m    
* Address book... F4    
A dialog box will open for the options just described, follow the instructions on the screen.    
* Set to current date Ctrl+Shift+h    
It will reset the date selector to the current date.    

#  View Menu Submenu Alt+ v

In this third menu we will have the following options:    

* See birthdays F5    
* See appointments F6    
* See recurring appointments Shift+F6    
* See repeat reminder Ctrl+F6    
* See anniversaries F7    
* See medicines F8    
* See recurring medicines Shift+F8    
Press Enter on the desired option to display it in a list.    
Press the applications key or shift+f10 to display the available options.    
Press Tab and then click the Close button or press the Escape or Enter key to close this dialog box and then return to the main program window.    
Note:    
When you create/edit a reminder, you will also notice 2 recurring types: (Recurring appointment and Recurring medicine)    
These two types of reminders can be set with recurrence: (Daily, Weekly, Yearly), depending on the week for Weekly, choice of day and choice of month will be activated for Yearly.    
You can set from 5 to 60 minutes, you will be notified in time and you will have the opportunity to, I don't know, change, get ready, and when the warning expires the real alarm will go off.    
Recurring reminders are smart, they move to the next equivalent date when they expire. For example, a recurring daily reminder, you will always find it the next day too, and so on.    
I haven't provided the ability to delete recurring reminders (for obvious reasons), but you can view them via the "View" menu.    
If you want to remove one, just activate Show the first "Date" column in the lists, excluding appointments and medications from the View menu.    
Next, select the type of recurring reminder you want to delete from the "View" menu and note its entry date, visible in the first column on the left.    
Finally, set this date in the main selector so you can see it and proceed with the deletion.    
Continuing with the View menu:    
* Show the first "Date" column in displayed lists, (Excluding appointments and medications) (unchecked by default)    
Seeing these dates is useful for easily finding reminders to change or delete them by setting the date from the main selector.    

# Settings Menu Submenu Alt+ s

In this fourth menu we will have the following options:    

* Set notifications Ctrl+Shift+n    
Press enter, a dialog box appears, move with "Tab" and "Shift+Tab" to move between controls, up and down arrows to change the parameter value.    
`Number of repetitions: 3`    
`Interval between repetitions (seconds): 8`    
`Use alarm: Alarm 01`    
`Enables reading of hours in 24-hour format`    
This is a checkbox to choose whether to set the format to 24 hours or 12 hours, the default is 24 hours.    
Press the spacebar to set the 12-hour format.    
`Enable date reading in European format`    
This is a checkbox to choose to set the date format to US or European, the default is European.    
Press the spacebar to set the US format.    
This dialog also contains these checkboxes:    
* Check for updates (selected by default)    
If this option is enabled, check for program updates at startup.    
Once the configuration is complete, press Enter or the "OK" button to validate the changes. To cancel the changes press Escape or the "Cancel" button.    

# Help Menu Submenu Alt+ h

In this fifth and final menu we will have the following options:    

* Program information... F1    
When you press the submit button on this item, a dialog box opens showing program information in a reading document.
Use the NVDA+b or Insert+b keys of the screen reader in the documentation to read this information again.    
Once done, press Tab and then click OK button or press Enter or Escape key to close this dialog box and then return to the main program window.    
* User manual... Shift+F1    
When you press Enter on this item, a window will open displaying the program help in a read-only editing html document in the default browser in your respective language if available, otherwise you will receive a warning message.    
Press Alt+F4 to close it.    
* Key shortcuts... F9    
When you press Enter on this item, a dialog box will open in which the program's keyboard shortcuts will be displayed in a read-only editing list, use the arrow keys to move through the list.    
Press Tab and then click the Close button or press the Escape or Enter key to close this dialog box and then return to the main program window.    
* Check for updates... Ctrl+Shift+U    
When you press Enter on this item, you will be notified if there are updates for the program, if so, follow the instructions on the screen.    

# 4.\ Additional information for the main window for the option "Reminder for the selected day:" <a name="toc4"></a>
When you change the date in the main window selector, if the selected date matches a reminder, a sonar sound will sound.    
However, the focus may shift to the list if a reminder has previously been selected.    
To avoid this inconvenience, you can deselect the reminder before proceeding, or enter the date directly following the order day, month, year or month, day, year, depending on the system language settings (and not those of the program ).    
In the selector you can navigate using the horizontal arrows.    
It is important to note NVDA does not speak the current position in the selector. We recommend pressing a vertical arrow: NVDA will communicate the date you set and provide updates as soon as you type a full day, month, or year.    
Sonar solves the problem of setting the initial date, instead of moving the focus to the list of reminders when there is one on that date, you hear the sound that notifies you and you can play with your date without problem :)    

# 5.\ How does the Address book work? <a name="toc5"></a>
Access to:    
`Edit Menu Submenu Alt+ e`    
then:    
`Address book... F4`    
When you press Enter on this option, a dialog box opens with the name:    
`Address book`    
This dialog box will contain the list of your contacts if you have added one, otherwise this list is empty.    
When you open the context menu in this dialog box by pressing the applications key located next to the right control key on most keyboards. On a keyboard without an applications key, press shift+f10 instead.    
Please note that some options are unavailable in the contact list depending on the context. You can press Enter on the option you want, so here are the options:    

* Add contact... Ctrl+N    
* Edit contact... F2    
* Delete contact... Del    
* Find contact... Ctrl+F3    
A dialog box will open for the menu options just described, follow the on-screen instructions.    
* Find next F3    
* Find previous Shift+F3    
Both of these options are based on the contact name you typed in the "Find contact" dialog box, so the search is performed with the next or previous match of the same name found in the address book list.    
* Send email to contact... Ctrl+e    
A dialog box will open for this option, follow the on-screen instructions.    

Please note that you can send an email to the contact if the contact's email has been entered in the edit field separated by a space at the beginning (and if necessary at the end), when editing the name of contact, for example. Otherwise, if there is no email in this edit box, this option will not be available to send it.    

If you have not set a default email program, the system will automatically display a dialog box allowing you to select the application to use to send the email.    

---

Thank you for reading this documentation!    

I wish you good use of the program ReminderApp (Reminder) 😉    
I would like to sincerely thank [Rémy Ruiz](mailto:remyruiz@gmail.com) for writing this documentation and translation of ReminderApp into French, English, Italian and Spanish and for his feedback and suggestions.    
