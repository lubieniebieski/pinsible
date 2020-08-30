# Pinsible - Ansible for your Raspberry Pi

I just wanted to make my RPi setup persistent and play a little bit with Ansible. Have fun!

## Setup

Disclaimer: this setup is tested on Mac OS.

1. Add your key to authorized keys on pi@ host. (or use `sshpass`)
2. `brew install ansible`
3. Create `hosts` file (take a look at `hosts.sample`)
4. `ansible-playbook main.yml -i hosts`

## Contact

Ping me at [@lubieniebieski](https://twitter.com/lubieniebieski) on Twitter.
