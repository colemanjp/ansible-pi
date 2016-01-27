# ansible_pi
The install of `python-dev` fails when run from the `iot.yml` playbook. Timeout? 
Run it once like this until I figure out what is wrong.

    ansible pi -u pi -k -b -i hosts -m apt -a "name=python-dev"

The playbook is what you normally run.

    ansible-playbook -k -i hosts iot.yml
