# Payroll System Priorities

#### Kei, Terrence, Julieon, Gabriel

### MUST

* The Accounting team and CFO have specified functionality and access to this program (Business)
    * It is required to define who has access and what type of functionality is necessary on the first release for the users in order for the payroll system to even ship within basic specifications.
    * This payroll program will be used specifically by accountants and the CFO, with separate functionality for each, such as data entry, auditing and review, data recording, and data output for use in other systems. All functions and systems of the program assume access by these specified users, and define what needs to be calculated, implemented, and output.

* The program uses US Dollars as the currency to be calculated (Business)
    * This is a basic requirement of the program that defines the data type being handled, and the location that the program is being used in, which will specify what needs to be input, output, and implemented.
    * The main calculations and data variables being used in this payroll program will be currency, and as such, USD is defined as the core value that is being used and calculated. Currency conversions, currency value, and data validation may all be required in the payroll system depending on currency data.

* Program follows Government regulations (Business)
    * Government regulations are extremely important when money is handled. The customer will always require the first release to be up to standards of regulation.
    * The program will follow US government regulations, including implementation of federal and state tax returns, building of accurate financial record structures, and proper calculation methods of finances, including deductions, credits, and other considerations.

* The program is in the English Language (Business)
    * All of the prompts and relevant data must be handled and stored in English because all of the employees will speak English. If the prompts were in other languages and not English, instructions would not be properly followed.
    * Properly translating all of the prompts would take unnecessary time and money. If it is necessary, it will be handled in future releases.

* The program must allow for the accounting team to input payroll records per employee (Functional)
    * This is a base functionality of the payroll system, and is required to bring in data for calculation of the payroll, which is not possible otherwise.
    * Only the accounting team would be capable of inputting/modifying the database. The individual employees would not be able to adjust old data, input new employees to the system, or make changes to the underlying database, without access.

* Calculations are made for salary, net pay, federal taxes, state taxes, medical contributions, Retirement Contributions, Deductions, etc. (Functional)
    * The main purpose specified by the customer for this system is to process and calculate payroll records and data, so the calculations are effectively the purpose the program, and cannot be released without this functionality.
    * Accounting department and the CFO should be able to see the total salaries, federal/state taxes, medical contributions, etc. so that they know how much total is being paid and how much they have to send to government/state for taxes, insurance company for medical etc.

* Payroll and Tax Documentation to be retained by the customer while the payroll system processes and outputs these documents (Functional)
    * The system requires that payroll data be input and output in order to function.
    * The system will access customer employee records and data, and output necessary calculations in a format that can be accessed by the user and the system again. This input and output payroll data will be retained by the customer, while the system will process it.

* The payroll system runs on 64bit desktop Windows and Macintosh computers (Functional/Implementation)
    * The system must be specified to run on specific systems to minimize range of the system, and make sure that all functions of the program will work properly on specified systems.
    * 64 bit Operating Systems allows for 16 general purpose registers instead of 8 as well as additional SSE registers, expanding memory allocation capabilities. The system also provides more than 4 GB of RAM for processing and 64bit data types.

* The system tracks/classifies all employees, including part-time, full-time, salaried, etc. (Functional)
    * This is crucial to the company, as failing to classify the company's employees could lead to serious harm for the company legally and financially as different rules and regulations apply to different employees based on their classification.
    * The system will calculate payroll depending on the specified employee's classification, and determine benefits, taxes, deductions, and so on.
### Should

* Visualization of the payroll data and system navigation will be presented in a menu (Non-Functional)
    * While the program is being compiled through command line, the system could benefit from having a menu that displays current records or commands or navigation to make it accessible to users. The first release focuses on the functionalities (e.g., input/output of data), and this visualization can be implemented in the second release.

* Program calculates employee pay while including bonuses, overtime, and other special income modifications (Functional)
    * While the customers would benefit from this feature, the accounting department could handle without the software if necessary. Therefore, it can be implemented in the second release.

* A standard customer business format W2 and other tax documents to be used for payroll processing (Functional)
    * While it would be convenient for the software to use standard tax formatting, as long as the data is stored in the system, there is no need to spend extra time and energy on optional data formatting.

* Program includes data checking mechanism for bad payroll records or entries (Implementation)
    * It is assumed that the users of this software understand how payroll and accounting works so it is not urgent that data checking procedures are implemented.

### Could

* Website created after software development to go along with the application (Users/Stakeholders)
    * A program run through command line as first project/release. However, a website version will be considered if the project is a success and the customers want to move forward as a future release.

* The company president/upper management can see report breakdowns of payroll records and audits (Users/Stakeholders)
    * Only the total salaries, federal/state taxes, medical contributions, etc. are required by accounting department and the CFO for the first release, but the reports of the details can be added in a future release.

* Employee paycheck frequency is calculated for individual users (Functional)
    * This release only focuses on the use of the accounting department and the CFO. If necessary, the use for individual employees will be added in the future release.

* The software processes information within the customers specifications (Non-Functional)
    * This is specifying that the program should be able to return or process information such as payroll or a record lookup within a reasonable time and accurately return the information to the user within seconds.

* Individual Employees have a read only access to view their own payroll records (Users/Stakeholders)
    * The payroll program is specifically accessed by accounting and CFO, so allowing employees to view their own payroll is not completely necessary. However, it would reflect normal payroll systems that allow employees limited access in a read-only fashion.

* Menu Navigation will be implemented to make payroll input, calculate, and specification accessible to the user (Functional)
    * While user accessibility is important, the program should function first, and unless requested specifically by the customer to include a menu system on the first release, it can wait until later.

### Won't

* The program creates a pdf. file view of the payroll record that they view (User/Stakeholders)
    * This is here because this can be a preference for the user as in some cases a pdf file might not be ideal so we won't make this feature into our initial build out of the program unless the customer request it.

* Program runs on mobile devices (Functional)
    * Due to the severity of this program and the information it will contain puts this company at a high security risk if we allow it to be accessed from a users mobile device and therefore we won't make this program accessible from a mobile device.
