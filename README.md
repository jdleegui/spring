## Download Spring STS(spring.io/tools/sts)
```
tar xvf spring-tool-suite-3.9.0.RELEASE-e4.7.0-linux-gtk-x86_64.tar.gz 
```
## Install Spring STS
```
Help > Eclipse Marketplace > Search 'STS'
Check if the newest version installed.
```
## Run sts
```
jdlee@LeeJD:~$  ~/Downloads/sts-bundle/sts-3.9.0.RELEASE/STS

```
## Environment
```
Window > Preference > 
```
## Create project
```
File > New > Spring MVC Project
Name:sts_basic Next
sts.basic.test
Finish
```
## Update Project
```
SampleWebApp > Maven > Update Project > OK
SampleWbpApp > Run > Run AS > Maven Install
```
## Add project to server
```
Servers | Server > Pivotal tc SErver Developer > Add and Remove
Add SampleWebApp to configured
Run Server 
```
## Confirm result
```
http://localhost:8080/SampleWebApp/
```
