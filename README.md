# Ansible Collection - sebw.gotify

This collection contains a module to send notifications to a Gotify server.

Example:

```
- gotify:
    url: https://gotify.example.org
    token: mytokenmustbevaulted
    title: My Ansible Notification
    msg: Ansible task finished
    priority: 4
```