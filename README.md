# VMI Phishing
Every year hackers are improvising and actively impersonating Lithuanian VMI (State Tax Inspection) organization

As every year hackers are using various methods to distribute phishing URL's - using SMS & sending Emails.    

In 2024 we see a second active campaign which happened in July.

## Phishing Emails same as last year are with QR code (blurred side of QR code):      

__QR code is used intentionally because users will need to use their phones and as we know most phones are without any AV.__    

![Screenshot 2024-07-15 081701](https://github.com/user-attachments/assets/5f7c8f75-3155-47f9-ade0-7bb9518920ea)    
![Screenshot 2024-07-15 081631](https://github.com/user-attachments/assets/c31ec081-2195-411d-8b1e-3cee8ff87fde)    

## QR codes - URL's / (IoC):
hxxps://myworkspace766a4.myclickfunnels[.]com/evmi-kliente    
hxxps://remoto.com[.]bo/ltitou    
__Both URL's redirects to the main phishing page:__ hxxps://e-vmlt-mano-kliente-lt.pages[.]dev/Autentifikavimas    

## Phishing page:

__Phishing page collects:__
- Personal identification number.
- Banking details.
- Phone number.

![Screenshot 2024-07-15 075528](https://github.com/user-attachments/assets/c5cc3878-e29c-4828-9e3f-a679c9f49f92)    
![Screenshot 2024-07-15 075657](https://github.com/user-attachments/assets/b102bec2-9e5d-445e-8fc1-a369947915a2)    
![Screenshot 2024-07-15 080037](https://github.com/user-attachments/assets/cc649af7-f572-478c-a019-ecfc9664ac41)    
![Screenshot 2024-07-15 080201](https://github.com/user-attachments/assets/b8d1e401-b8be-41f3-b793-77bdfa600a25)    

__VirusTotal status 2024-07-15:__    

![Screenshot 2024-07-15 080534](https://github.com/user-attachments/assets/c140df30-3c81-4293-9232-7e70c006723d)    

## Let's Dig Deeper:    

__Domain information - we see that it's hiding behind Cloudflare:__    

![Screenshot 2024-07-15 081145](https://github.com/user-attachments/assets/07d222ea-e7b1-4b53-acf3-fd1975054ee1)    

__But wait there's more:__    

Checking this specific Cloudflare IP address - we see multiple different phishing pages (impersonating various pages - many of those are already blocked by Google)    

![Screenshot 2024-07-15 081036](https://github.com/user-attachments/assets/947bc09f-8224-4222-a365-b72040daaa78)    

![image](https://github.com/user-attachments/assets/c02c1681-3136-4500-8f2c-34bee01dd27a)







