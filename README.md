Requirements
============
- [requests](http://docs.python-requests.org/en/latest/user/install/)

Installation
============
```bash
pip install valid_pymail
```

Example Use
===========
```python
In [1]: from valid_pymail.validator import MailgunEmailValidator

In [2]: mv = MailgunEmailValidator('pubkey-1a2b3d4e5f67d8dc8a76c1bee5e1ef9c')

In [3]: mv.validate_email('dummy@google.com')
Out[3]: 
{u'address': u'dummy@google.com',
 u'did_you_mean': u'dummy@googlemail.com',
  u'is_valid': True,
   u'parts': {u'display_name': None,
     u'domain': u'google.com',
       u'local_part': u'dummy'}}
```

Questions or Comments
=====================
Leave a message on the repo, submit PR's, or get ahold of me at
mmalocha13@gmail.com.
