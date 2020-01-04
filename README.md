13.232.207.177 </br>


sudo su </br>
useradd devopsuser  </br>
passwd devopsuser  </br>

123selenium  </br>


cd /etc/ssh  </br>
ls  </br>
vi sshd_config </br>
/password </br>

i to insert. Esc to go back to command mode, :wq to save and quit. </br>

service sshd restart  </br>


## Install java  

```
yum install java-1.8*  
vi .bash_profile  
JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64
export JAVA_HOME 
PATH=$PATH:$JAVA_HOME 

```



echo $PATH </br>

## Install Jenkins
yum -y install wget </br>
wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo  </br>
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key  </br>
yum install jenkins -y  </br>


find / -name javac  </br>
