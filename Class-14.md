# Class 14

## Intro to password hashing 
   1. Define the term “hashing”.
      is a technique commonly used in computer science and cryptography. It involves taking some information
      (often referred to as a "message" or "data") and transforming it into a fixed-size string of characters, 
      usually made up of numbers and letters. This resulting string is called a "hash value" or simply a "hash.

   2. Explain to a non-technical friend what a hash function does to a password.

      Imagine your password is like a secret code for your online accounts, and you want to keep it safe. So, you use
      a special tool called a "hash function" that turns your password into a unique code.
 
     Think of it like a magical blender for words. You put your password into this blender, and it mixes it up to
     create a special jumble of letters and numbers. This jumble is your password's secret disguise, and it doesn't 
     look anything like your actual password.
     Now, when you sign up for a website or log in, the website doesn't store your real password. Instead, 
     it keeps the jumbled-up version that the blender made. So, even if someone sneaks into the website's computer,
     they can't understand your password because it's in this strange jumbled form.
     When you enter your password to log in, the website takes what you typed, blends it with the magic blender the
     same way, and checks if the jumbled result matches the one it stored. If they match, you get access.


## bcrypt overview

  1. What does it mean to ‘salt’ a password?
     A ‘salt’ adds a very long string of bytes to the password. So even though a hacker might gain access to one-way 
     hashed passwords, they should not be able to guess the ‘salt’ string.
 
  2. What piece of information would a hacker need to access in order to find the ‘salt’ string for your passwords?
     If a hacker has access to your source code, they will easily be able to find the ‘salt’ string for passwords.

## jBCrypt 

  1. How does the Blowfish block cipher handle the increased computation speed of new computers?
     as implemented in jBCrypt and originally designed by Bruce Schneier, includes a parameter called the "cost factor"
     or "work factor." This cost factor determines the number of encryption iterations or rounds performed by the 
     Blowfish algorithm when hashing a password.

  2. What are the issue with the two most commons password hashes for Java (“Java password hash” and
     “Java password encryption”)?
     - Unsalted Hashes
     - Reversible Encryption

