
**launch Ec2 Instance**

   - `ubuntu image`
   - `t2.medium`
   - `security group with 8080 port`
   - `30 GIB Volume`

- **Java install**
```

sudo apt update
sudo apt install fontconfig openjdk-17-jre
java -version

```
- **Jenkins Install on linux**
```
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
  https://pkg.jenkins.io/debian/jenkins.io-2023.key
echo "deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]" \
  https://pkg.jenkins.io/debian binary/ | sudo tee \
  /etc/apt/sources.list.d/jenkins.list > /dev/null
sudo apt-get update
sudo apt-get install jenkins

```
- `put <public Ip :8080>`
  
- `sudo cat <link>`
  
- `copy password and past login jenkins`

```
```
