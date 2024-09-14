Pykraken
=========

Deploys a Kubernetes CronJob for scheduled execution of pykraken.

Requirements
------------

An API token and secret from Kraken.

Role Variables
--------------

kraken_api_token: "..."
kraken_api_sec: "..."

pykraken_namespace: pykraken
pykraken_schedule: "0 * * * * "
pykraken_r_value_target: .33
pykraken_investment_count: 3
pykraken_investment_volume: 100

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
