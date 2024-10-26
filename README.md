# Project Name

![Login](login_img.jpg)

## Overview

This project is designed to validate user input, specifically focusing on name and email validation, ensuring that names meet length requirements and emails adhere to common domain formats. The script offers two primary functions:

- `validate_name`: Ensures that user names are strings with more than two characters.
- `validate_email`: Checks for the presence of an '@' symbol and validates the email's top-level domain.

## Features

- **Name Validation**: Confirms if a name is correctly formatted.
- **Email Validation**: Ensures emails have standard domains like `.org`, `.com`, `.edu`, and others.
- **Domain List**: Supports multiple common top-level domains for flexible email validation.

## Getting Started

### Prerequisites

Ensure you have Python 3 installed to execute the code.

### Installation

Clone this repository and navigate to the project directory:

```bash
git clone https://github.com/your-username/project-name.git
cd project-name
```

### Usage

In the script, you'll find two main functions: `validate_name` and `validate_email`. You can call these functions to validate user inputs as follows:

```python
# Import functions
from script_name import validate_name, validate_email

# Validate name
is_valid_name = validate_name("John Doe")
print(f"Name Valid: {is_valid_name}")

# Validate email
is_valid_email = validate_email("johndoe@example.com")
print(f"Email Valid: {is_valid_email}")
```

### Example

```python
# Sample usage
print(validate_name("Alice"))  # Returns True
print(validate_email("alice@example.org"))  # Returns True
print(validate_email("alice@wrongdomain.xyz"))  # Returns False
```

## Contributing

Feel free to fork this project, make your enhancements, and submit a pull request.

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Your Name - [Your Email](mailto:your-email@example.com)
