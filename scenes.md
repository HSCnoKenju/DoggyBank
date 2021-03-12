Actors and Events
* User
* Start of period
* End of period
* First entry 


 Title | initial setup
  ---- | -----
Description| (R14F) user on the first entry should set the track method and the initial value or import data
Actor | User, \<\<event>>First Entry 
Relationships|set initial value, import data, select track method, clear data
Preconditions| the system has no data about the user
Postconditions| the system knows the initial value for the next period and the track method
Main scene| 1. import data<br>OR<br> 1. set initial value and period <br> 2. set track method
Alter scene |1. failed to import data<br>
Not functional requirement|
To define|

 

 Title | set the initial value and period duration
  ---- | -----
Description| a
Actor | User, \<\<event>> Start of period
Relationships| initial setup, mnually, store the value for the next period,compiling form, the same as last period
Preconditions|
Postconditions|initial value and period duration set
Main scene|1.manually <br>OR<br>1. compiling the form with the following fields:<br> a. Input all the money you earnt this month<br> b. exclude the fixed life's cost (home loan, taxes, bills)<br> c. on the subtotal, enstabilish in percentage how much you want to save, how much you are willing to invest, and how much you want to spend the following month<br>d. take the percentage of what you want to spend times you subtotal as the starting value <br>OR<br>1. the same of last period<br>THEN<br> 2. store the value for the next period
Alter scene |
Not functional requirement|
To define|


Title | select track method
  ---- | -----
Description| a
Actor | User
Relationships|initial setup, open the options
Preconditions|
Postconditions|
Main scene|1. track the exact value<br>OR<br>1. track only successful or unsucessfully overspend
Alter scene |
Not functional requirement|
To define|


Title | clear data
  ---- | -----
Description| empty all the data stored by the application
Actor | User
Relationships| initial setup, open the options
Preconditions|
Postconditions|start initial setup
Main scene|1. delete all the stored data such as: initial value, remaning duration, spendable money, monthly tracking, transaction history.
Alter scene |
Not functional requirement|
To define|

Title | import data
  ---- | -----
Description| a
Actor | User
Relationships| open the options, initial setup
Preconditions|
Postconditions|
Main scene| 1. select the file to read<br>2. read from the file
Alter scene | file is not in the right format
Not functional requirement|
To define|

Title | export data
  ---- | -----
Description| a
Actor | User
Relationships| open the options
Preconditions|
Postconditions|
Main scene|1. confirm to export the data
<br>2. encrypt the data<br> 3. serialize the data to the phisical storage
Alter scene |
Not functional requirement| data encryption on exit data
To define|


Title | track the user monthly score
  ---- | -----
Description| a
Actor | User, \<\<event>> End of period
Relationships|
Preconditions|
Postconditions|
Main scene|1. popup of congratulation (or try next period)<br>2.save this month score
Alter scene |
Not functional requirement|
To define|


Title | see the spendable money left at anytime
  ---- | -----
Description| a
Actor | User
Relationships|
Preconditions|
Postconditions|
Main scene|
Alter scene |
Not functional requirement|
To define|

Title | see the past month score at anytime
  ---- | -----
Description| a
Actor | User
Relationships|
Preconditions|
Postconditions|
Main scene|
Alter scene |
Not functional requirement|
To define|


Title | register one transaction
  ---- | -----
Description| a
Actor | User
Relationships|
Preconditions|
Postconditions|
Main scene|1. user input the last transaction <br>2. spendable money goes down of the same value<br>3. spendable money can be negative<br>4. UI change when the money is negative
Alter scene |
Not functional requirement|
To define|

