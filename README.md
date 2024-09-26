Here is a basic `README.md` file for your Insurance Management System project:

```markdown
# Insurance Management System

This project is an Insurance Management System built with PHP and SQL. It allows admins, agents, and clients to manage various aspects of insurance policies, payments, and plans.

## Project Structure

The project directory is organized as follows:

```
Insurance-Management-System-master/
├── DBMS/
│   ├── Admin/
│   │   ├── Admin-Login.php
│   │   ├── Admin-Register.php
│   │   ├── AdminMenu.php
│   │   ├── footer.php
│   │   ├── header.php
│   │   ├── includes/
│   │   │   ├── AddNewPlan-inc.php
│   │   │   ├── Admin-Login-inc.php
│   │   │   ├── Admin-Register-inc.php
│   │   │   ├── changePlan-inc.php
│   │   ├── Plan/
│   │   │   ├── AddNewPlan.php
│   │   │   ├── PlanDetails.php
│   │   ├── View/
│   │   │   ├── editPlan.php
│   │   │   ├── ViewAgentList.php
│   ├── Agent/
│   │   ├── Agent-Login.php
│   │   ├── Agent-Register.php
│   │   ├── AgentMenu.php
│   │   ├── footer.php
│   │   ├── header.php
│   │   ├── includes/
│   │   │   ├── Agent-Login-inc.php
│   │   │   ├── Agent-register-inc.php
│   │   │   ├── DeletePolicy-inc.php
│   │   │   ├── UpdatePolicyHolder-inc.php
│   │   ├── ManagePolicy/
│   │   │   ├── AddNewPolicy.php
│   │   │   ├── AddNewPolicyHolder.php
│   │   │   ├── DeletePolicy.php
│   │   │   ├── EditPolicyHolder.php
│   │   │   ├── ManagePolicy.php
│   │   │   ├── UpdatePolicy.php
│   │   ├── PolicyOptions/
│   │   │   ├── BusinessReport.php
│   │   │   ├── CommissionReports.php
│   │   │   ├── PlanPresentation.php
│   │   │   ├── SearchPolicyDetails.php
│   │   ├── PremiumPaymentRecord/
│   │   │   ├── AddPaymentRecord.php
│   │   │   ├── PremiumPaymentRecord.php
│   │   │   ├── ShowRecordBook.php
│   ├── css/
│   │   ├── style.css
│   ├── images/
│   │   ├── img3.jpg
│   │   ├── img5.jpg
│   │   ├── img6.jpg
│   ├── database.php
│   ├── index.php
├── l7.sql
```

## Files Description

### DBMS
- **Admin**: Contains PHP scripts and includes files for admin functionalities such as login, registration, plan management, and viewing agent lists.
- **Agent**: Contains PHP scripts and includes files for agent functionalities such as login, registration, policy management, payment record management, and policy options.
- **css**: Contains the CSS stylesheet for the project.
- **images**: Contains image files used in the project.
- **database.php**: Database connection script.
- **index.php**: The main entry point of the application.

### Root Directory
- **l7.sql**: SQL script for setting up the database.

## How to Run

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Insurance-Management-System.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Insurance-Management-System
   ```
3. Set up the database:
   - Import the `l7.sql` file into your MySQL database.
   - Update the `database.php` file with your database credentials.
4. Deploy the project to your web server (e.g., Apache).
5. Open the application in your web browser:
   ```sh
   http://yourserver/Insurance-Management-System/DBMS/index.php
   ```

## Contributing

If you would like to contribute to this project, please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the MIT License.

```

Feel free to modify and expand this `README.md` file as needed to fit your project's specific details and requirements.
