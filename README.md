# MobileAppDevProjetRomainKersuzan

Here we will use a user to log in. It has a username and a password. 
So he will have access to all the accounts

![Login](https://user-images.githubusercontent.com/72665312/110253989-61089200-7f8d-11eb-8b78-2fe7da7bf373.jpg)

If there is an error in his username or passwords. A toast would appear to inform him

![LoginError](https://user-images.githubusercontent.com/72665312/110254066-c78db000-7f8d-11eb-8265-433204d641d8.jpg)

Once logged in you have access to all the accounts and you can also refresh the page to update the accounts.

![Connected](https://user-images.githubusercontent.com/72665312/110254094-f3a93100-7f8d-11eb-9560-d16162aad4e9.jpg)
![AccountList](https://user-images.githubusercontent.com/72665312/110254097-f99f1200-7f8d-11eb-8ee0-442540ca95f1.jpg)


If the internet connection is lost the data is saved in a local database.
So the user always has access to this data.

![Disconnected](https://user-images.githubusercontent.com/72665312/110254133-18050d80-7f8e-11eb-80e2-f8b80bf6c3c6.jpg)


SECURITY 
 
Here all safety aspects have been respected :

- The API and the different communications are of course HTTPS.
- Here the url of our api is encoded in base 64. 
- The user's connection is secure it is hashed sha256



