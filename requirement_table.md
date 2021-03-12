Requirement ID | Description | Type
:--------------: | -------------- | --------------
R1F| A the start of the period, the user can set the __initial value__ and __period__ duration manually| Functional
R2F | Set the __initial value__ and __period__ duration compiling the form | Functional
R3F | The __initial value__ and __period__ duration cannot be modified during the __period__ | Functional
R4F | __user__ can __registry__ each __transaction__ he made during the period| Functional
R5F | __user__ can see the __spendable money__ left at anytime| Functional
R6F | When a __transaction__ is __registred__, the __spendable money__ should go down of the same value | Functional
R7F | The __spendable money__ can be negative | Functional
R8F | There should be a viewable hint when the __spendable money__ is negative| Functional
R9F | Set the __initial value__ as the same as the last __period__ | Functional
R10F | Track the user monthly score | Functional
R11F | Track method: only if you successfully managed to spend less than the __initial value__| Functional
R12F | Track method : show how much you differed from the goal | Functional
R13F | user can see the past month score at anytime | Functional
R14F | user on the first entry should set the track method and the initial value or import data | Functional
R15F | user can open an option menù and perform the following action: clear data, change track method. The clear data should take the user back to first entry state| Functional
R16F | user can choose to export and import the data | Functional
R1NF | outgoing data full encrypted| Non functional
---



## Vocabolary
Term | Definition | Synonimus
------- | --------| ----------
initial value | the money set from user as starting value to display | goal
form | input: monthly income, monthly cost, percentage of investing, saving, spending<br>output: __initial value__ | 
registry  | send the data to the system | registred 
transaction | any type of spending the user made outside of the __fixed cost__|
fixed cost | example: home loan, bills<br>money that you cannot chose to not spend| 
spendable money | result of the __initial value__ minus all the __registred__ __transaction__| 
user | person using the application |
period | amount of time in which you should not spend more money over the __initial value__|
track | store somewhere so the user can retrieve and visualize the data|
monthly | for each __period__ (default thought as one month)|
score | success or not to keep the spending lower the __initial value__ |
first entry | first time the __user__ enter into the app |