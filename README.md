13.232.207.177



sudo su
useradd devopsuser
passwd devopsuser


123selenium

cd /etc/ssh
ls
vi sshd_config
/password

i to insert. Esc to go back to command mode, :wq to save and quit.

I
:wq
service sshd restart


----------------java ----
yum install java-1.8*

vi .bash_profile

JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64. 
export JAVA_HOME
PATH=$PATH:$JAVA_HOME


echo $PATH

--jenkins---
yum -y install wget
wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key
yum install jenkins -y


find / -name javac
