🔥👑 VIP BOT V10 👑🔥

🚀 FREE FIRE AUTOMATION BOT 🚀

<p align="center">
<img src="https://img.shields.io/badge/VERSION-V10-red?style=for-the-badge">
<img src="https://img.shields.io/badge/FREE%20FIRE-AUTOMATION-orange?style=for-the-badge">
<img src="https://img.shields.io/badge/PYTHON-100%25-blue?style=for-the-badge">
<img src="https://img.shields.io/badge/STATUS-ACTIVE-green?style=for-the-badge">
</p><p align="center">
<img src="https://wallpapercave.com/wp/wp8539097.jpg" width="90%">
</p>---

🌟 VIP BOT V10 (2DAY)

🔥 Powerful Free Fire Automation Bot
⚡ Super Fast Performance
💎 VIP System Enabled
🛡 Secure & Smooth Working

This bot is designed to automate several in-game room actions and provide a smooth automation experience.

---

✨ FEATURES

🌸 Auto Room Join
🌸 Auto Invite System
🌸 Auto Emote System
🌸 Custom Room Name
🌸 Fast Spam System
🌸 Smooth & Secure System
🌸 Live Status Control
🌸 Auto Restart System

---

📦 INSTALLATION (TERMUX)

Run the following commands in Termux:

pkg update -y
pkg install git python -y

# Remove old installation if exists
rm -rf $HOME/.ar
rm -f $PREFIX/bin/ar

# Clone fresh copy
git clone https://github.com/Ariyan20267/Ariyan_bot.git $HOME/.ar

# Install requirements
pip install --upgrade pip
pip install -r $HOME/.ar/requirements.txt

# Create permanent command
cat << 'EOF' > $PREFIX/bin/ar
#!/data/data/com.termux/files/usr/bin/bash
if [ ! -d "$HOME/.ar" ]; then
    git clone https://github.com/Ariyan20267/Ariyan_bot.git $HOME/.ar
fi

cd $HOME/.ar
git pull > /dev/null 2>&1

if [ -f "requirements.txt" ]; then
    pip install -r requirements.txt > /dev/null 2>&1
fi

python ARIYAN.py
EOF

chmod +x $PREFIX/bin/ar

---

▶ RUN BOT

After installation simply run:

ar

The bot will automatically start.

---

⚙ STATUS CONTROL SYSTEM

This bot uses a Live Status Check System.

If status = ON → Bot will run normally.
If status = OFF → Bot will automatically stop.

This allows the developer to control the bot remotely.

---

🧠 DEVELOPER

👑 ARIYAN

💻 Python Developer
🔥 Free Fire Automation Bot Creator

---

<p align="center">
💖 MADE WITH LOVE 💖
</p>
