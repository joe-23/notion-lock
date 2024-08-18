[![en](https://img.shields.io/badge/lang-en-red.svg)](https://github.com/Marcello09/notion-lock/blob/main/README.md)

# notion-lock

Simple add-on for Notion that encrypts and decrypts plain text using a password.
It uses AES encryption in Browser, no data is send to any server during encryption or decryption. All runs locally on your machine memory ;D

It is only possible to recover the data by typing the text and the correct password used to encrypt the data. 
This allows for multiple passwords to be used for different text.

# How-to

## Adding it to notion

1. Add the URL https://marcello09.github.io/notion-lock/en as an embedded view on any page of Notion.
2. Resize the frame to your liking.

## Encrypt text

1. Type a password or passfrase to encrypt your data, you must remember this password in order to recover (decrypt) the data.
2. Type the text you wish to encrypt.
3. Choose the checkbox “Encrypt Text”.
4. Press the button “Generate Text”.
5. Copy the text below Result, this is your encrypted data, or press the button “Copy to clipboard”.
6. Save the text anywhere you wish on Notion.

## Decrypt text

1. Type the password or passfrase you used to encrypt your text.
2. Copy the encrypted text to the textarea field.
3. Choose the checkbox “Decrypt Text”.
4. Press the button “Generate Text”.
5. Thats it! Your secret data is now available to you!

# Forking the project

To ensure continued access to this tool, you can fork the original repository to your GitHub account and set up GitHub Pages on your forked project. This way, you're not dependent on the original repository's availability.

The entire script is contained within a single index.html file, so it can also be hosted independently of GitHub Pages if you have a hosting service.

Here is a how to setup github pages on a project in case you don´t know how: [Quickstart for Github Pages](https://docs.github.com/en/pages/quickstart)

Disclaimer: The add-on runs entirely in your browser's memory using AES encryption. There is no way to recover encrypted data if you lose your password.

Project forked from Marcello09/notion-lock.
