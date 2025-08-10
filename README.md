# Payroll Calculator with Overtime

## Description

A Java program that calculates **employee payroll** based on the number of hours worked and hourly rates.
It supports **different pay rates** for regular hours and overtime hours, making it useful for businesses that follow overtime pay rules.

## Features

* Accepts user input for:

  * Employee name
  * Hours worked
  * Hourly rate for regular hours
  * Overtime rate multiplier (e.g., 1.5×)
* Calculates:

  * Regular pay (up to 40 hours)
  * Overtime pay (hours above 40)
  * Total pay (regular + overtime)
* Displays a detailed payroll summary.

## Formula Used

$$
\text{Regular Pay} = \text{Hours Worked (≤ 40)} \times \text{Hourly Rate}
$$

$$
\text{Overtime Pay} = \text{Overtime Hours} \times \text{Hourly Rate} \times \text{Overtime Multiplier}
$$

$$
\text{Total Pay} = \text{Regular Pay} + \text{Overtime Pay}
$$

## Usage

1. Compile the program:

   ```bash
   javac PayrollCalculatorOvertime.java
   ```
2. Run the program:

   ```bash
   java PayrollCalculatorOvertime
   ```

## Example

```
Enter Employee Name: Sarah Lee  
Enter Hours Worked: 45  
Enter Hourly Rate: 20  
Enter Overtime Multiplier: 1.5  

--- Payroll Summary ---
Employee Name: Sarah Lee  
Regular Hours: 40  
Overtime Hours: 5  
Regular Pay: 800.0  
Overtime Pay: 150.0  
Total Pay: 950.0
```

## Technologies Used

* Java (JDK 8 or above)

