# Payroll System Priorities

#### Kei, Terrence, Julieon, Gabriel

### MUST

* The Accounting team and CFO must have custom functionality and access to this program
 * Defining who has access, and what type of functionality is necessary on the first release for those users is required in order for the payroll system to even ship within basic specifications.
 * This payroll program will be used specifically by accountants and the CFO, with separate functionality for each, such as data entry, auditing and review, data recording, and data output for use in other systems. All functions and systems of the program assume access by these specified users, and define what needs to be calculated, implemented, and output.

* The program uses US Dollars as the currency to be calculated
  * This is a basic requirement of the program that defines the data type being handled, and the location that the program is being used in, which will specify what needs to input, output, and implemented.
  * The main calculations and data variables being used in this payroll program will be currency, and as such, USD is defined as the core value that is being used and calculated. Currency conversions, currency value, and data validation may all be required in the payroll system depending on currency data.

* Program must follow Government regulations
  * Government regulations, especially when handling money, are extremely important factors to consider for most companies, and the customer will always require the first release to be up to standards of regulation.
  * Government regulations may include anything from tax rates, to record structures, to calculation methods, and while some of these things may be provided by the customer (such as the tax rates), there may be different things that need to be included depending on the country. Certain deductions, credits, and employee requirements differ depending on the country, and these must be taken into account when calculating payroll.

* The program must be in the English Language
* The program must allow for the accounting team to input payroll records per employee
* Calculations must be made for net pay, federal taxes, state taxes, medical contributions, Retirement Contributions, Deductions, etc
* Payroll and Tax Documentation must be retained by the customer
* The payroll system must run on 64bit desktop computers (Windows/Macs)
* The system must track all employees, including part-time, full-time, etc


### Should

* Menu page should be very simple and easy to access (for user accessibility)
  * While user accessibility is important, the program should function first, and unless requested specifically by the customer to be as user friendly as possible on the first release, it can wait until the second one.

* On the page, there should be a page for the menu (a list of things that they can see, like payment history)
 * While the program is being compiled through command line, the system could benefit from having a menu that displays current records or commands or navigation to make it more accessible to users.

* Program should be able to calculate employee pay while including bonuses, overtime, and other income modifications
* A standard customer business format W2 and other tax documents should be used for payroll processing
* Program should have some sort of data checking mechanism for bad payroll records or entries

### Could

* Website development could be created after to go along with the application
* The company president/upper management could see detailed, easily accessed report breakdowns of payroll records and Audits
* Employee paycheck frequency could be calculated for individual users (Right now the accounting team enters this data when necessary
* The software could process information within the customers specifications
* Individual Employees should have a read only access to view their own payroll records
 * The payroll program is specifically accessed by accounting and CFO, so allowing employees to view their own payroll is not completely necessary, however, it would reflect normal payroll systems that allow employees more limited access in a read-only fashion.

### Won't

* The program could create a pdf. file view of the payroll record that they view
* Program runs on mobile devices