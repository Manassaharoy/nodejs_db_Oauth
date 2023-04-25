
# Node js with mongoose and oAuth. 

This is a reatu to go template for nodejs with mongodb and oAuth. Read the instructions before starting and changelogs to see changes

# Features 

- MVC structure
- 2 types of encryption & decryption middleware. one is of AES and another one 
- response middleware to make the response sending structure same for all api point.
- oAuth 2.0 available
- error handling middleware with enum HTTP error codes
- monitor app by visiting url: /status
- a colorful console log function


### Encryption type:
- **OPTION 1** The encryption algorithm used here is Advanced Encryption Standard (AES) which is a symmetric encryption algorithm. It is a widely used encryption standard and considered to be secure.
- **OPTION 2** This code is using the Advanced Encryption Standard (AES) algorithm for encryption and decryption. Specifically, it is using AES with a 256-bit key size in Cipher Block Chaining (CBC) mode with PKCS7 padding. The encryption key is generated by hashing a secret key string using the SHA256 algorithm.


## Script run sequence

Install packages

```
  npm i
```
change the followings in .env file before running the program.
- DATABASE_URL : "URL string of databse"
- ENCRYPTION_STATUS: "TRUE or FALSE"

### Run 

Start the server on development

```bash
  npm run test
```
Start the server

```bash
  npm start
```
## Prisma commands:
- After creating//modifying a schema use command to migrate ``` npx prisma migrate dev --name init --create-only ```
- after migration run deploy command ``` npx prisma migrate deploy ```


# Colorful terminal codes

```
case 1: red
case 2: green
case 3: blue
case 4: yellow 
case 5: cyan 
case 6: magenta
default: white
```

