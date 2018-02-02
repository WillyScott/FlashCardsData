# FlashCardsData
Json files for flash cards upload

How to: 
1. Use Google Docs Sheets to type in data.
2. First row should have strings "front" and "back".
3. Freeze the first row, set word wrapping, and increase the size of the cells.
4. Following this to add script to Sheets - http://blog.pamelafox.org/2013/06/exporting-google-spreadsheet-as-json.html
5. Run the script to create JSON modify if with card attribute.
6. The data for Swift_Keywords comes from https://medium.com/the-traveled-ios-developers-guide/swift-keywords-v-3-0-1-f59783bf26c

Updated instructions:
Add this script 
https://gist.github.com/pamelafox/1878143

Google has added some security to make it harder to add the script to your Google Sheets.
The steps are

In Google Sheets .

go to Tools\Script editor

Paste this script and save the script so you can use the script
in other sheets.
Refresh the sheet and the script should show in
the menu as "Export JSON"

Select "Export JSON"  and "Export JSON for this sheet"

A dialog will display

"Authorization Required
A script attached to this document needs your permission to run"

another dialog displays for different accounts if you have them

"Choose an account"

Select your account

Another dialog displays

"This app isn't verified .....  Learn more

Advanced                BACK TO SAFETY

Read the learn more if you want more information.

Select "Advanced"  link

On the same dialog select "Go to Untitled project(unsafe)

Another dialog displays

Select "Allow" at the bottom of the screen to run the script.

The JSON output will display in a new window.











