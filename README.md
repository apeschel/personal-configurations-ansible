Role Name
=========

Provides a quick way to push out personal configs to a host.

Requirements
------------

None at this time.

Role Variables
--------------

There is one variable that is to be configured:

```
user: {
  name: apeschel,
  comment: "Aaron Peschel"
}
```

This will create a user with the given information and will configure their home directory with their personal configs

Dependencies
------------

No Dependencies at this time.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - {
             role: apeschel.personal_configurations,
             user: {
               name: apeschel,
               comment: "Aaron Peschel"
             }
           }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
