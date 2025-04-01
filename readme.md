# HELLO PROFESSOR!! THIS IS MY HOMEWORK 7

## REQUIRED SUBMISSIONS: <br>

1.) Adding the QR code image that links to your own GitHub homepage that you generate to the readme.md file, so that it appears below :

![MyQRCode](https://github.com/user-attachments/assets/e06b044e-5974-4e81-88a2-decfde6da78a)

2.) Adding an image of viewing the log of successfully creating the QR code below:

- In VS code terminal:

![Screenshot 2025-03-31 at 11 53 49 PM](https://github.com/user-attachments/assets/d125254a-2051-4cff-a3ef-9583604a1df0)


- In Docker container:

![Screenshot 2025-03-31 at 11 58 06 PM](https://github.com/user-attachments/assets/564acb7b-8a74-44f7-986f-0e84a79b7c58)

## Outputs of commands:

- Building the Image :

```
    docker build -t my-qr-app .
```

![Screenshot 2025-03-31 at 11 51 35 PM](https://github.com/user-attachments/assets/c0b6d5a1-bf5b-42db-a94c-2cc431295766)


- Running the Container with Default Settings

```
    docker run -d --name qr-generator my-qr-app
```