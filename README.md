# nocodb-as-service

```bash
sudo vi /etc/systemd/system/nocodb.service
# Paste nocodb.service contents
sudo systemctl daemon-reload
sudo systemctl enable nocodb.service
sudo systemctl start nocodb.service
```
