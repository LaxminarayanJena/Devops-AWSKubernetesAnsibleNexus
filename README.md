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


----------------java ----  </br>
yum install java-1.8*  </br>

vi .bash_profile  </br>

JAVA_HOME=/usr/lib/jvm/java-1.8.0-openjdk-1.8.0.191.b12-1.el7_6.x86_64. </br>
export JAVA_HOME </br>
PATH=$PATH:$JAVA_HOME </br>


echo $PATH </br>

--jenkins--- </br>
yum -y install wget </br>
wget -O /etc/yum.repos.d/jenkins.repo https://pkg.jenkins.io/redhat-stable/jenkins.repo  </br>
rpm --import https://pkg.jenkins.io/redhat-stable/jenkins.io.key  </br>
yum install jenkins -y  </br>


find / -name javac  </br>
