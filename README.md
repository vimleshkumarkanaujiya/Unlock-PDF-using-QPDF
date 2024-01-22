# Unlock-PDF-using-QPDF
A tool that manipulates PDF files on the command line

## Install OpenSSL and QPDF Library

```
sudo apt update && sudo apt install openssl qpdf
```
## Run the command
```
qpdf --decrypt --password=your_owner_password input.pdf output-unlocked.pdf
```
Here, change `"your_owner_password"` to the password known to you, and change the name `"input.pdf"` to your PDF file's name.
