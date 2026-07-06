# TICHI Web Automation Testing

This project is developed using Selenium WebDriver with Python and Pytest.

It automates the Login and Sign Up functionalities of the TICHI Web Application.

## Technologies Used

- Python
- Selenium WebDriver
- Pytest
- Page Object Model (POM)
- Allure Report

## Project Structure

```
TICHI_WEBSITE/
│── pages/
│── tests/
│── utilities/
│── allure-results/
│── README.md
```

## Test Modules

### Login
- Valid Login
- Invalid Password
- Empty Email
- Empty Password
- Forgot Password
- Login Button Validation

### Sign Up
- Email Validation
- First Name Validation
- Password Validation
- Password Mismatch
- Mobile Number Validation
- Terms & Conditions Validation

## Run the Project

```bash
python -m pytest -v
```

## Generate Allure Report

```bash
python -m pytest --alluredir=allure-results
allure serve allure-results
```

## Test Result

- Total Test Cases: 18
- Passed: 18

## Author

Kanyaka Pandi
