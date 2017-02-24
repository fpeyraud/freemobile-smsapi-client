freemobile-smsapi-client
========================

API client for the Free Mobile SMS notification service

Theses clients send SMS notifications via [Free Mobile](http://mobile.free.fr) mobile broadband company native SMS-notification API.
This service can only send SMS to line's owner: it cannot be used to send SMS to any mobile number, group or massive spam.

Shell Client
------------

### usage:

```
    uptime | send-notification.sh 0623456789
```

### Configuration :

Edit `send-notification.sh` and set the following variables:

* `USER_LOGIN`
* `API_KEY`

Edit a file (`/etc/free_sms_apikeys`) to list the different contacts

```
     0623456789 01928374 9zzlUR87j6HyzqK
     0609876543 01928374 9zd8DJZl71dyzqK
```
