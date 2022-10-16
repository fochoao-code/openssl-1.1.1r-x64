# OpenSSL 1.1.1r x64 binaries

OpenSSL running and the tests completed:

![image](https://user-images.githubusercontent.com/108408523/196027215-94bde9d0-830d-417d-9efb-39fc2f24faad.png)

OpenSSL 1.1.1r x64 binaries for Windows.

I built the binaries for Windows x64, the files are inside binaries, drop them in the folder:

C:\

Press Yes to all.

After this You have to alter the Environment Variables, so here is a tutorial in images to do it.

Now here they are.

![image](https://user-images.githubusercontent.com/108408523/196027285-c154bfff-d1a0-4d60-bae7-789826211d7f.png)

click on settings.

![image](https://user-images.githubusercontent.com/108408523/196027330-d7c9875f-8bac-474c-b0ba-47489b46c4dd.png)

Click on About.

![image](https://user-images.githubusercontent.com/108408523/196027355-9889f33d-d555-4ad4-9de3-ce008078b9b3.png)

Now on Advanced System Settings. After that on Environment variables.

![image](https://user-images.githubusercontent.com/108408523/196027403-59f21b9e-e2f3-4407-b9ab-912d175ebe21.png)

Now press on New... then on Variable Name write OPENSSLDIR then on Variable value "C:\Program Files\Common Files\SSL"

![image](https://user-images.githubusercontent.com/108408523/196027462-a5813c8d-1b46-47aa-ac64-11cfd2e52867.png)

After that press on New... again, then on Variable Name write ENGINESDIR then on Variable value "C:\Program Files\OpenSSL\lib\engines-1_1"

![image](https://user-images.githubusercontent.com/108408523/196027509-b4e06be9-8c6d-4446-ac06-4dcca6812b7f.png)

Add all these folders on Path variable, now reboot and run cmd.exe, type openssl, then version -a, after that play with it.
Enjoy this!

![image](https://user-images.githubusercontent.com/108408523/196027588-97d87682-5cc0-4105-8d60-69edaf5e611e.png)
