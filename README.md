Ansible - Run Playbook
======================

This is an example of how to run Ansible v2 Playbook programatically.


Usage
-----

```
$ cd env
$ ../run.py

PLAY [Test play] ***************************************************************

TASK [Debug task] **************************************************************
ok: [localhost] => {
    "msg": "Hello world!"
}

PLAY RECAP *********************************************************************
localhost                  : ok=1    changed=0    unreachable=0    failed=0
```


Resources
---------

* [Running Ansible 2 Programmatically](https://serversforhackers.com/running-ansible-2-programmatically)


Author
------

Jiri Tyr


License
-------

MIT
