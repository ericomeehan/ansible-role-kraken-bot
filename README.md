Kraken Bot
=========

Scheduled algorithmic cryptocurrency tradting using the Kraken API

Requirements
------------

None.

Role Variables
--------------

kraken_bot_namespace: kraken-bot
schedule: "0 * * * * "

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: ericomeehan.kraken-bot }

License
-------

BSD

Author Information
------------------

Eric O'Neill Meehan
