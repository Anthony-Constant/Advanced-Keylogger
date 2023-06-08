# Advanced_Keylogger.py

## Introduction

This is an advanced keylogger script created in Python by Anthony Constant. The script allows the user to monitor keystrokes on a keyboard and capture screenshots of the computer monitor. The script is also able to encrypt the data it captures and send it to a specified email address.

## How It Works

This keylogger script uses the `pynput` library to control and monitor devices, and it uses the `PIL` library to take screenshots.

The script logs each key typed on the keyboard and saves it to a text file called `key_log.txt`. The script also takes screenshots of the computer monitor and saves them to image files.

The script then encrypts the data it captures using the `cryptography` library and sends it to a specified email address using the SMTP protocol.

## Usage

To use this keylogger script, you will need to have Python installed on your computer.

Once you have Python installed, you can download the script and run it in your terminal or IDE.

You will need to provide a few parameters for the script to run:

- `email_address`: The email address that you want to send the key log to
- `password`: The password for the email account
- `toaddr`: The email address that you want to send the key log to
- `file_path`: The file path where you want to save the key log and screenshots
- `time_iteration`: The amount of time, in seconds, between each email sent
- `number_of_iterations_end`: The number of times the email should be sent

Once you have provided these parameters, you can run the script and it will begin monitoring keystrokes and capturing screenshots. The data will be encrypted and sent to the specified email address at the specified intervals.

## References

- [https://www.kaspersky.co.uk/resource-center/definitions/keylogger](https://www.kaspersky.co.uk/resource-center/definitions/keylogger)

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was created by [Anthony Constant](https://anthonyconstant.co.uk/). 
