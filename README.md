Role Name
=========

timezone

Role Variables
--------------

```

# Default timezone.  Must be a valid tz database time zone.
timezone: UTC

```

Example Playbook
-------------------------

```

---
- hosts: all
  roles:
  - abh.timezone

  vars:
   timezone: America/Los_Angeles

```

```

---
- hosts: all
  roles:
  - abh.timezone

  vars:
   timezone: UTC

```


License
-------

Apache 2.0

Author Information
------------------

Ask Bjørn Hansen (from work by Ryan Yates)
