Beanstalkd
==========

Install beanstald

Requirements
------------

none

Role Variables
--------------

- `beanstalkd_wal_dir` - Path to the WAL dir, default to `/srv/beanstalk/wal`

Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: kuon.beanstalkd }

License
-------

MIT
