<h1>Advanced_Keylogger.py</h1>
<h2>Introduction</h2>
<p>This is an advanced keylogger script created in Python by Anthony Constant. The script allows the user to monitor keystrokes on a keyboard and capture screenshots of the computer monitor. The script is also able to encrypt the data it captures and send it to a specified email address.</p>
<h2>How It Works</h2>
<p>This keylogger script uses the pynput library to control and monitor devices, and it uses the PIL library to take screenshots. </p>
<p>The script logs each key typed on the keyboard and saves it to a text file called key_log.txt. The script also takes screenshots of the computer monitor and saves them to image files.</p>
<p>The script then encrypts the data it captures using the cryptography library and sends it to a specified email address using the SMTP protocol.</p>
<h2>Usage</h2>
<p>To use this keylogger script, you will need to have Python installed on your computer. </p>
<p>Once you have Python installed, you can download the script and run it in your terminal or IDE.</p>
<p>You will need to provide a few parameters for the script to run:</p>
<ul>
  <li>email_address: The email address that you want to send the key log to</li>
  <li>password: The password for the email account toaddr: The email address that you want to send the key log to</li>
  <li>file_path: The file path where you want to save the key log and screenshots</li>
  <li>time_iteration: The amount of time, in seconds, between each email sent</li>
  <li>number_of_iterations_end: The number of times the email should be sent</li>
</ul>
<p>Once you have provided these parameters, you can run the script and it will begin monitoring keystrokes and capturing screenshots. The data will be encrypted and sent to the specified email address at the specified intervals.</p>
<h2>References</h2>
<p><a href="https://www.kaspersky.co.uk/resource-center/definitions/keylogger">https://www.kaspersky.co.uk/resource-center/definitions/keylogger</a></p>
<h2>Credits</h2>
<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="https://anthonyconstant.co.uk/">anthonyconstant.co.uk/</a></p>
<h2>License</h2>
<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
