<<<<<<< HEAD
# 🌐 Host Your Own Server Locally with XAMPP & Localtonet

This guide helps you set up a local web server using **XAMPP** and make it publicly accessible using **Localtonet**. Perfect for beginners looking to test web apps, share demos, or receive webhooks from external services.

---

## 📦 Requirements

Before we start, make sure you have:

- ✅ A PC with Windows, macOS, or Linux
- ✅ [XAMPP](https://www.apachefriends.org/index.html) installed
- ✅ [Localtonet](https://localtonet.com/) account and CLI tool

---

## 🚀 Step 1: Install & Configure XAMPP

1. Download and install XAMPP from [apachefriends.org](https://www.apachefriends.org/index.html).
2. Open the **XAMPP Control Panel**
3. Start the `Apache` module.

🧪 **Test Your Setup**  
Go to your browser and open `http://localhost` — you should see the XAMPP welcome page.

📁 Place your files in:  
```
C:\xampp\htdocs\
```
Then visit `http://localhost/index.html` or `index.php` to test.

---

## 🌍 Step 2: Expose Localhost to the Internet using Localtonet

1. Sign up for a free account at [localtonet.com](https://localtonet.com/)
2. Download the **Localtonet CLI**
3. Open a terminal and run:

```bash
localtonet http --port 80
```

4. You’ll get a public URL like:

```
https://yourname.localtonet.com
```

Now anyone with the link can access your localhost project!

---

## 🧪 Example Project

You can clone this repository and place its contents into your `htdocs/` folder:

```bash
git clone https://github.com/yourusername/host-local-server-xampp-localtonet.git
```

Place the files inside:
```
C:\xampp\htdocs\
```

Then access it at:
- `http://localhost`
- Or your public localtonet URL

---

## 📸 Screenshots

> *(Add your own images in `assets/` folder)*

- XAMPP Control Panel  
  ![](./assets/xampp-control-panel.png)

- Localtonet Public URL Terminal  
  ![](./assets/localtonet-terminal.png)

---

## ✅ Use Cases

- Testing PHP or static websites
- Sharing quick demos with others
- Receiving webhook responses from services like Stripe, GitHub, or Discord
- Working with mobile devices on the same project

---

## 🔒 Security Notes

⚠️ **Important:** This setup is intended for development use only. Exposing your local server to the public internet can pose serious security risks if not properly managed. Never use this for production!

---

## 🛠 Troubleshooting

- ❌ **Port 80 in use?**
  - Change to another port in XAMPP config, or close apps like Skype/Teams.
  - Run localtonet with: `localtonet http --port 8080`

- ❌ **Nothing showing up on the public URL?**
  - Make sure your file is in the correct directory.
  - Double-check that Apache is running and not blocked by a firewall.

---

## 📄 License

This project is licensed under the [MIT License](./LICENSE).

---

## 🤝 Contributing

Feel free to submit issues or pull requests to improve this guide!

---

## 🔗 Resources

- [XAMPP Official Site](https://www.apachefriends.org/index.html)
- [Localtonet](https://localtonet.com/)
- [Localtonet Docs](https://docs.localtonet.com/)
- [PHP Beginner Guide](https://www.php.net/manual/en/tutorial.php)
=======
# Host-local-server-xampp-localtonet
A beginner-friendly guide to hosting your local server with XAMPP and making it publicly accessible using Localtonet. Ideal for testing, demos, and learning web development basics.
>>>>>>> 6e27f8c8e47e92ac7f71d386d5e04c9fa6aa6107
