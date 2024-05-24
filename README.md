# Python_mini_project

Title : Details Form Entry and Retrieval
Technologies used : Python, MySQL

- The Details From Entry and Retrieval has 3 GUIs
- First UI acts as the Main page connecting both the Details entry page and the Data retrieval page.
- Second UI to enter the data and insert it into the Database. Basic data checks were implemented in order to prevent Bad data insertion.
- Third UI is to retrieve saved data from the Database
- To merge the three UIs, Toplevel window method from Tkinter is used.
- 3 separate classes were made. 1 - Main Page (App), 2 - Data entry page (insert_window) and 3 - Data retrieval (retrieve_window)

Note**
BEFORE RUNNING THE FILE PLEASE BE CONNECTED WITH THE MySQL SERVER LOCALHOST
ENTRY WINDOW : 
- All the details asked for in the entry page are mandatory fields and cannot be empty.
- First Name and Last Name cannot contain numerical values.
- Date of Birth should be entered in the YYYY-MM-DD format.
- Mobile cannot contain alphabetical characters.
- PAN number should be like - Example : MHJUN9876I. starting with 5 uppercase alphabets followed by 4 numerical values and ending with a single uppercase alphabet.

RETRIEVAL WINDOW :
- Can be searched with either only first name or only last name.
- Can be searched with both first name and last name for accurate results.
