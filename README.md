# Notification

![Python v3.7](https://img.shields.io/badge/Python-3.7-green?style=for-the-badge)
[![License: AGPL v3](https://img.shields.io/badge/License-AGPL_v3-blue.svg?style=for-the-badge)](https://www.gnu.org/licenses/agpl-3.0)

This repo documents the service of notification.

### How to start the service

```
sudo docker-compose up
```

### How to use the service

```
curl --header "Content-Type: application/json"   --request POST   --data '{"sender":"abc@indocresearch.org","receiver":"tiangao0611@gmail.com", "message":"tttttttt"}'   http://10.3.9.240:5065/v1/email
{
    "result": "Email sent successfully. "
}
```
