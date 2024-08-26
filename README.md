# Exchange-Server-Emulation
My guide on setting up push notifications using EAS.


I have gotten Push notifications to work on my universities email address, by setting up a google cloud vm to intercept mail, and then emulate a microsoft exchange server, allowing push notifications on iOS, and other mobile devices. 

Basic Idea:
- Create Free VM With Google Cloud , etc.
- Setup apache and open up ports for smtp, imap, and https.
- Download and set up z-push, and create the nescessary routes and ailiases.
- Add domain name/ ddns record
- Setup SSL cert using LetsEncrypt, or similar.
- Setup z-push to use smtp, adjust ping rate, imap settings and setup logging.
- Finally you can add the "Exchange Server" to ios mail.

In the coming weeks I will write up a guide here in this repo, as well as share some configuration files, an possibly in the future create a docker image or create a bootstraping script to make the process easier, as there was not a lot of documentation available.
