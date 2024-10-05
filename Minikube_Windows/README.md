
Download and install VirtualBox 7.1.2 from VirtiualBox.org .

Got the dependency error install python core and Win32api

Install python 3.12.6 and execute below commands from cmd (run as administrator)
py -m pip install pywin32
python.exe -m pip install --upgrade pip

![image](https://github.com/user-attachments/assets/6462031f-ae5f-41d1-84a3-459cc8f374b7)


Set the path variable for VirtualBox in environmental variables.

![image](https://github.com/user-attachments/assets/2dd11dfc-6aa6-44f9-b533-3051907a912f)

Install Kubectl

Download and install minikube

![image](https://github.com/user-attachments/assets/1f0bc562-4096-4b0c-ac72-c80f52cf090d)

Start minikube

Got below error

![image](https://github.com/user-attachments/assets/428ce860-cef8-447b-a606-5324c05010ca)

Because i didnt had closed the VirtualBox Installation Wizard. After closing the VirtualBox installtion wizad , i was able to start the minikube.

![image](https://github.com/user-attachments/assets/6cadc864-b208-42be-9510-e04229090c4f)

Kubectl get nodes

![image](https://github.com/user-attachments/assets/99c087ed-fc55-4bc3-96df-d18f3aa625d0)

If we are facing any issue with minikube , stop minikube and start again.

Minikube stop 
minikube start 
![image](https://github.com/user-attachments/assets/8e23ec50-ec39-4396-b27d-6785ad33b1cd)











