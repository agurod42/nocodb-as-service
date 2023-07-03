# nocodb-as-service

```bash
sudo vi /etc/systemd/system/nocodb.service
# Copy and paste nocodb.service contents (Remember to change ExecStart and WorkingDirectory)
sudo systemctl daemon-reload
sudo systemctl enable nocodb.service
sudo systemctl start nocodb.service
```
