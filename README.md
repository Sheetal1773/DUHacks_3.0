# DUHacks_3.0
## Theme - Healthcare
### Title - Blood Bank Management System
#### Problem Statement - 
##### People die due to lack of donated blood. Donors are available but not at the right place or the seeker cannot find blood at the right time. Problem solved by creating a program in Python-MySQL Connectivity. Old Blood banking systems don’t follow the actual needs of users.

# Blood Bank Management System

This project is a Blood Bank Management System developed using Python, Django, HTML, CSS, and JavaScript. It aims to streamline the process of blood donation by providing a centralized platform for donors, patients, hospitals, and blood banks.

# Functions

## Admin
- To create an admin account, use the following command:
  ```bash
  py manage.py createsuperuser
  ```
- Upon login, the admin can view the unit of blood for each blood group, number of donors, blood requests, approved requests, and total blood units on the dashboard.
- Admin has CRUD (Create, Read, Update, Delete) functionality for donors and patients.
- Admin can approve or reject donation requests, which affect the blood stock accordingly.
- Admin can approve or reject blood requests, which also impact the blood stock.
- Admin can view the history of blood requests and update the units of a particular blood group.

## Donor
- Donors can create accounts with basic details.
- After login, donors can donate blood, pending approval from admin.
- Donors can view their donation history and blood request status.

## Patient
- Patients can create accounts without admin approval.
- Upon login, patients can request blood of specific blood groups and units.
- Patients can view their blood request history with statuses.

---

## How to run this project:
- Install Python (version 3.11 recommended) and ensure "Add to Path" option is checked during installation.
- Download the project folder.
- Navigate to the project folder in your terminal/command prompt.

## Requirements

To run this project, you need to have Python installed on your system. Additionally, you'll need to install the required Python packages listed in the `requirements.txt` file.

To install the required packages, run the following command:

`pip install -r requirements.txt`

## Running the Project

Follow these steps to run the Blood Bank Management System:

1. Clone the repository to your local machine:

```bash
git clone https://github.com/Sheetal1773/DUHacks_3.0.git
```

2. Navigate to the project directory:
```bash
cd BloodBankManagement
```

3. Install the required packages using pip:
```bash
pip install -r requirements.txt
```
4. Make the migrations:
```bash
py manage.py makemigrations
```
```bash
py manage.py migrate
```
```bash
py manage.py runserver
```
   
5. Run the Django development server:
```bash
python manage.py runserver
```


5. Access the project in your web browser by visiting [http://localhost:8000/](http://localhost:8000/).

## Usage

Once the project is running, you can use the Blood Bank Management System to:

- Register as a donor or patient
- Search for donors
- Manage donor and patient profiles

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request with your changes.

Thank you for using the Blood Bank Management System!
