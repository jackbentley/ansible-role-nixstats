# Ansible Role: Nixstats

Installs nixstatsagent using the `nixstatsagent.sh` install script.

Configures `/etc/nixstats.ini` config file.

## Requirements

None.

## Role Variables

Make sure to set the `nixstats_user_token` variable to your user token in NixStats.

All other variables are optional and can be found in `defaults/main.yml`.

## Dependencies

None.

## Example Playbook

    - hosts: server
      roles:
        - { role: jackbentley.nixstats }

## License

MIT / BSD
