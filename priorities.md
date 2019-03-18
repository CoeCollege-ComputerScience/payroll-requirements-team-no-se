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
    * All of the prompts and relevant data must be stored stored in English because all of the employees will speak English. I the prompts were in other languages and not English, instructions would not be properly followed.
    * Properly translating all of the prompts would take unnecessary time and money.

* The program must allow for the accounting team to input payroll records per employee
    * Without access, via the payroll software, to the underlying database, the customer would have no way of adjusting old date or inputing new employees to the system.

* Calculations must be made for salary, net pay, federal taxes, state taxes, medical contributions, Retirement Contributions, Deductions, etc
    * First, these calculations are made individually. Each employee should be able to see their final net pay so that they can see their deductions.
    * Accounting department and the CFO should be able to see the total salaryies, federal/state taxes, medical contributions, etc. so that they know how much total is being paid and how much they have to send to goverment/state for taxes, insurance company for medical etc.

* Payroll and Tax Documentation must be retained by the customer
    * The input and output payroll data needs to be retained by the customer, and the system only processes them and doesn't store them itself. If the customers want the system to store the data, it can be added in a future release.

* The payroll system must run on 64bit desktop computers (Windows/Macs)
    * Creating and running our program on a 64-bit Operating System will give the application access to more memory and allow our program to run and process a little faster than if it was on a 32-bit operation system.

* The system must track/classify all employees, including part-time, full-time, etc
    * This is crucial to the company as failing to classify the company's employees could lead to serious harm for the company legally and finacially as different rules and regulations apply to different employees based on their classification.

### Should

* Menu page should be very simple and easy to access (for user accessibility)
    * While user accessibility is important, the program should function first, and unless requested specifically by the customer to be as user friendly as possible on the first release, it can wait until the second one.

* On the page, there should be a page for the menu (a list of things that they can see, like payment history)
    * While the program is being compiled through command line, the system could benefit from having a menu that displays current records or commands or navigation to make it more accessible to users.

* On the page, there should be a page for the menu (a list of things that they can see, like payment history)
    * While the program is being compiled through command line, the system could benefit from having a menu that displays current records or commands or navigation to make it more accessible to users.

* Program should be able to calculate employee pay while including bonuses, overtime, and other income modifications
    * The customer would benefit from the software automatically calculating employee pay while including bonuses, overtime, and other income modifications, however, the customers accounting department could do it by hand if need be.

* A standard customer business format W2 and other tax documents should be used for payroll processing
    * While it would be convenient for the software to use standard tax formatting, as long as the data is stored in the system, there is no need to spend extra time and energy on optional data formatting.

* Program should have some sort of data checking mechanism for bad payroll records or entries
    * It is assumed that the users of this software understand how payroll and accounting works so it is not urgent that data checking procedures are implemented.

### Could

* Website development could be created after to go along with the application
    * A program run through command line as first project/release. However, a website version will be considered if the project is a success and the customers want to move forward as a future release.

* The company president/upper management could see report breakdowns of payroll records and audits
    * Only the total salaryies, federal/state taxes, medical contributions, etc. are required by accounting department and the CFO for the first release, but the reports of the details can be added in a future release.

* Employee paycheck frequency could be calculated for individual users (Right now the accounting team enters this data when necessary)
    * This release only focuses on the use of the accounting department and the CFO. If necessary, the use for indivisual employees will be added in the future release.

* The software could process information within the customers specifications
    * This is specifying that the program should be able to return or process information such as payroll or a record lookup within a resonable time and accurately return the information to the user within seconds.

* Individual Employees should have a read only access to view their own payroll records
    * The payroll program is specifically accessed by accounting and CFO, so allowing employees to view their own payroll is not completely necessary, however, it would reflect normal payroll systems that allow employees more limited access in a read-only fashion.

### Won't

* The program could create a pdf. file view of the payroll record that they view
    * This is here because we felt that this is more of a preference for the user as in some cases a pdf file might not be ideal so we won't make this feature into our initial build out of the program unless the customer request it.

* Program runs on mobile devices
    * Due to the severity of this program and the information it will contain puts this company at a high security risk if we allow it to be accessed from a users mobile device and therefore we won't make this program accessible from a mobile device.
