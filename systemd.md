# Create systemd service

1. Insert real bot token in monitoring/rg_bot.service
2. Copy file rg_bot.service to /etc/systemd/system/
3. systemctl daemon-reload
4. sudo systemctl enable rg_bot.service
5. sudo systemctl start rg_bot.service
6. sudo systemctl status rg_bot.service

# Unblock reboot for sudoers
sudo chmod u+s /sbin/shutdown