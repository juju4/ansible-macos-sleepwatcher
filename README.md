[![Actions Status - Master](https://github.com/juju4/ansible-macos-sleepwatcher/workflows/AnsibleCI/badge.svg)](https://github.com/juju4/ansible-macos-sleepwatcher/actions?query=branch%3Amaster)
[![Actions Status - Devel](https://github.com/juju4/ansible-macos-sleepwatcher/workflows/AnsibleCI/badge.svg?branch=devel)](https://github.com/juju4/ansible-macos-sleepwatcher/actions?query=branch%3Adevel)

# macOS sleepwatcher ansible role

Ansible role to setup sleepwatcher on macOS.
http://www.bernhard-baehr.de/
"a command line tool (daemon) for OS X that monitors sleep, wakeup and idleness of a Mac. It can be used to execute a Unix command when the Mac or the display of the Mac goes to sleep mode or wakes up, after a given time without user interaction or when the user resumes activity after a break or when the power supply of a Mac notebook is attached or detached."

## Requirements & Dependencies

### Ansible
It was tested on the following versions:
 * 1.9
 * 2.0
 * 2.2
 * 2.10

### Operating systems

MacOS 10.11, 10.12, 10.15

## Example Playbook

Just include this role in your list.
For example

```
- host: all
  roles:
    - juju4.macos-sleepwatcher
```

## Variables

Nothing specific for now.

## Continuous integration

This role has a travis basic test (for github) and Github action.

## Troubleshooting & Known issues


## License

BSD 2-clause
