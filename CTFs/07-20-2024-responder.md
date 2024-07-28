## Responder

Room Link:  https://app.hackthebox.com/starting-point



![htb-responder-0](https://github.com/user-attachments/assets/f93b8360-8992-4992-bd37-c37414e2e6f7)

- WinRM, Custom Applications, Protocols, XAMPP, SMB, Responder, PHP, Reconnaissance, Password Cracking, Hash Capture, Remote File Inclusion, Remote Code Execution


![htb-responder-4](https://github.com/user-attachments/assets/c1670118-394a-4a4d-9f95-192011a4956a)


![htb-responder-5](https://github.com/user-attachments/assets/8576e225-26af-4053-8882-645ac33742af)

## TASK 1

Q: When visiting the web service using the IP address, what is the domain that we are being redirected to?
A: unika.htb

![htb-responder-2](https://github.com/user-attachments/assets/11082c85-e89b-4153-8ba9-4430c7f60f66)

## TASK 2

Q: Which scripting language is being used on the server to generate webpages?

A: php


## TASK 3

Q: What is the name of the URL parameter which is used to load different language versions of the webpage?

A: page

![htb-responder-3](https://github.com/user-attachments/assets/6b9bf0f2-a8c2-49bb-8b93-fbc8e437af78)



## TASK 4

Q: Which of the following values for the `page` parameter would be an example of exploiting a Local File Include (LFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"

A: ../../../../../../../../windows/system32/drivers/etc/hosts


![htb-responder-7](https://github.com/user-attachments/assets/e44084a0-07a2-41bc-bd91-9ddf3b6a46cc)


## TASK 5

Q: Which of the following values for the `page` parameter would be an example of exploiting a Remote File Include (RFI) vulnerability: "french.html", "//10.10.14.6/somefile", "../../../../../../../../windows/system32/drivers/etc/hosts", "minikatz.exe"

A: //10.10.14.6/somefile


## TASK 6

Q:  What does NTLM stand for?

A: New Technology Lan Manager

## TASK 7

Q: Which flag do we use in the Responder utility to specify the network interface?

A: -I

![htb-responder-6](https://github.com/user-attachments/assets/f0c9d92a-3e7b-4910-97a0-fa1630ef88f5)


![htb-responder-8](https://github.com/user-attachments/assets/313e8c24-38c5-456b-a689-d2a651770c36)



![htb-responder-9](https://github.com/user-attachments/assets/7c965080-1a36-4940-8f05-bfecb674aa3b)

![htb-responder-10](https://github.com/user-attachments/assets/de10d345-1fc9-49bc-8352-9608f54d2c77)


![htb-responder-11](https://github.com/user-attachments/assets/fe8c6f16-735e-4871-b307-470eff65877f)


![htb-responder-12](https://github.com/user-attachments/assets/fedefd5b-ee7d-4058-8a55-5aa2c3ab6a48)




## TASK 8

Q: There are several tools that take a NetNTLMv2 challenge/response and try millions of passwords to see if any of them generate the same response. One such tool is often referred to as `john`, but the full name is what?.

A: John The Ripper



![htb-responder-13](https://github.com/user-attachments/assets/c930ff9a-c5a9-4fc9-aeb4-c4cb702aaa9a)


![htb-responder-14](https://github.com/user-attachments/assets/7cca0089-b3ad-4ee0-a682-695cfca1b62b)


## TASK 9

Q:  What is the password for the administrator user?

A: badminton


![htb-responder-14](https://github.com/user-attachments/assets/bba75e58-d0f6-4746-95ed-8976ac3acccd)

## TASK 10

Q: We'll use a Windows service (i.e. running on the box) to remotely access the Responder machine using the password we recovered. What port TCP does it listen on?

A: 5985

![htb-responder-15](https://github.com/user-attachments/assets/092f3bdc-813a-4102-b8a5-be25e3a62c86)


## Root Flag

![htb-responder-16](https://github.com/user-attachments/assets/f83482e5-ca8b-4f9e-a44c-74c9ace7c837)


![htb-responder-17](https://github.com/user-attachments/assets/66c04030-b7b2-4b23-9453-e6b9beaa1884)
