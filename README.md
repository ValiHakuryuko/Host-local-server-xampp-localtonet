# Host Your Own Server Locally with XAMPP & Localtonet

This guide helps you set up a local web server using **XAMPP** and make it publicly accessible on the net using **Localtonet**. Perfect for beginners looking to test web apps, share demos, or receive webhooks from external services.

## Requirements
- A PC with Windows, macOS, or Linux
- [XAMPP](https://www.apachefriends.org/index.html) installed
- [Localtonet](https://localtonet.com/) account

## Step 1: Install & Configure XAMPP
1. Download and install XAMPP from [apachefriends.org](https://www.apachefriends.org/index.html).
2. Open the **XAMPP Control Panel**
3. Start the `Apache` module.
4. To test if it workes, go to your browser and open `http://localhost`, you should see the XAMPP welcome page

Place your files in any folder "C:\xampp\htdocs\" for example.
Then visit `http://localhost/index.html` or `index.php` to test.

## Step 2: Expose Localhost to the Internet using Localtonet
1. Sign up for a free account at [localtonet.com](https://localtonet.com/)
2. Download the **Localtonet CLI**
3. Open a terminal and run: "localtonet http --port 80"
4. This should give a public URL of the format "https://yourname.localtonet.com"

Now anyone with the link can access the localhost project
