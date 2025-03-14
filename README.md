# Advanced-File-Folder-Encryption
Advanced File &amp; Folder Encryption with Email integration

## Prerequisites
 - Formspree (https://formspree.io)
 - curl

✅ Features
- Encryption and Decryption for both file and folder
- Email is sent with the password on successfully encryption
- Password is never stored
- Integrated with email(Formspree)
 

## Setup
1. curl must be installed for this script to send emails using Formspree
    ```bash
   sudo apt update && sudo apt install -y curl
   ```
2. CONFIGURED Formspree Log in to Formspree:
     ```bash  
   Make sure your Form ID is correct (f/mpwzekgg).
   Your email is verified.
   Form is set to "Anyone can submit".
   ```
3. Formspree Email Configuration:
    ```bash
   Ensure your endpoint: (https://formspree.io/f/xyz) is correct
   replace with your Endpoint and Email
    
   FORMSPREE_ENDPOINT="https://formspree.io/f/xyz"
   TO_EMAIL="ashwinbshetty373@gmail.com"
   ```

   


