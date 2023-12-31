# remote ssh-linux

fix config file & fix path:

![image](https://github.com/ASalad42/remotessh-linux/assets/104793540/d2365da7-15ca-4849-aad7-fef696e0f6ea)

fix bad owner or permissions issue:
- https://stackoverflow.com/questions/49926386/openssh-windows-bad-owner-or-permissions/58275268#58275268
- https://github.com/microsoft/vscode-docs/issues/3210
- https://www.virtualizationhowto.com/2022/02/bad-owner-or-permissions-on-ssh-config-windows-10/#:~:text=To%20get%20past%20the%20Bad,sshd_config%20file%20changes

connect to remote via ssh 


- `sudo apt update`
- `sudo apt install nodejs`
- `sudo apt install npm`
- `sudo npm install -g pnpm`


- wget copylinkaddress

```
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa
sudo apt update
sudo apt install python3.9
sudo apt install python3-pip
```

- echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
- source ~/.bashrc

- echo "alias python='python3.9'" >> ~/.bashrc
-  restart your terminal or run source ~/.bashrc to apply the changes.



fixing poetry upgrade error:

- create new env > `python3.9 -m venv venv`
- `source venv/bin/activate`
- `python -m pip install --upgrade pip setuptools`
- `python -m pip install -r requirements.txt`
- `pnpm run rebuild`


After exporting the Lightsail instance to Amazon EC2, you can use the exported snapshot to create a new Amazon EC2 instance, troubleshoot issues, or recover data.

https://repost.aws/knowledge-center/lightsail-export-linux-instance-ec2
