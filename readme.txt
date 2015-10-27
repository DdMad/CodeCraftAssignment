Announcement feature for CodeCraft from Team09

Member Name				Matric. No.
Huang Ziyu				A0119456Y
Narinderpal Singh Dhillon		A0097416X
Wang Zhipeng				A0119414L
Zhang Ji				A0119391A



Task 1 folder contain the code that the announcement will popup using JavaScript native popup box (alert).
Changes:
bin/www: line 39, line 303-321
gui.js: line 1840-1857, line 3199-3422, line 6337-6341



Task 2 folder contain the code that the announcement will popup using CodeCraft style popup box.
Changes:
bin/www: line 39, line 303-321
gui.js: line 1840-1855, line 3197-3582, line 6497-6501


Both tasks only modify bin/www and gui.js 2 files.

The announcement button is in the setting menu in share box window, below the ‘leave group’ option.

Once a client create a sharebox, he or she can send an announcement to all of the members in this sharebox(except himself or herself). 
However, the rest in this share box cannot send announcement since they are not creator (this will pop up a announce failure window).
Once an announcement has been sent, the rest will receive the announcement popup.
Once some receiver close the announcement popup, the server will update the number of receivers that have read the announcement.
Then if all receivers have read the announcement, the server will send an announcement to the announcer(sender) to notify him or her that all his announcement have been read by receivers.
