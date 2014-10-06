python-mailgun-validator
========================
A Python wrapper for the mailgun email validator RESTful API

Requirements
============
- requests

Example Use
===========
```python
from validator import MailgunEmailValidator

mv = MailgunEmailValidator('pubkey-1a2b3d4e5f67d8dc8a76c1bee5e1ef9c')

result = mv.validate_email('dummy@google.com')
```
