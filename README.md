# KeyAuth Login Script

This Python application uses the KeyAuth API to verify user licenses. It also features a simple loading bar, user information display, and license verification.

### Requirements

- Python 3.x
- Required Python library:
  - `pyautogui`

### Clone the Project

Clone the project to your local machine.

### Install Dependencies

Use the following command to install the required libraries:

```bash
pip install pyautogui
```

### Enter Your API Information

In the project file, enter your KeyAuth API details in the following fields:

```python
keyauthapp = api(
    name = "YourAppName",
    ownerid = "YourOwnerID",
    secret="YourSecretKey",
    version = "1.0",
    hash_to_check = getchecksum()
)
```

### Testing

After completing all the steps, you can test the application by running the following command:

```bash
python main.py
```

## Usage

- When the application starts, you will be prompted to enter a license key.
- Once the correct license key is entered, you can view your user information and active subscriptions.

**Note:** This code only handles the login portion. After the user logs in, you can add different actions or features as needed, such as using this as a simple console tool for validation purposes.

## Contributing

If you'd like to contribute to this project, please leave a star. We appreciate any and all contributions!

## License

This project is licensed under the [MIT License](LICENSE).