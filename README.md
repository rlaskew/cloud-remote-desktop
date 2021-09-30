# cloud-remote-desktop

## READER NOTE: No warranty express or implied, use at your own risk
WIP Repo: Notes and scripts for how to remove desktop into Cloud based servers

## Amazon Linux 2 on AWS Notes

### using AL2
https://aws.amazon.com/premiumsupport/knowledge-center/ec2-linux-2-install-gui/

## vncpasswd in userdata
https://askubuntu.com/questions/328240/assign-vnc-password-using-script

# future get started script commands
yum update -y
amazon-linux-extras install mate-desktop1.x
bash -c 'echo PREFERRED=/usr/bin/mate-session > /etc/sysconfig/desktop'
yum install tigervnc-server -y 
amazon-linux-extras install epel
yum install chromium -y

