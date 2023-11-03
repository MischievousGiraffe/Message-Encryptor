# Message-Encryptor
The Message Encryptor Project Using Node.js

Message Mixer Node Project Forked from Codecademy.com
**Must be run on node.js**

## TUTORIAL: ##
* Three different ciphers can be chosen to encrypt messages with the message-mixer.js.
* A Super Encoder can be chosen to encrypt messages with super-encoder.js: 

## SEE EXAMPLES BELOW ##
* A “Caesar Cipher” in which the characters of the input message are shifted alphabetically by a given amount.
* A “Symbol Cipher” in which select characters from the input message are replaced with visually similar symbols.
* A “Reverse Cipher” in which each word of the input message is reversed in place.
* A "Super-Encoder" in which all the input message is fed through all 3 ciphers listed above and the result is an encoded message. 
The new encoded message can then be inserted with the "decode" argument to reveal the original input without the "encoding". 
 

### Caesar Cipher with an argument of 6:
> $ node message-mixer.js caesar 6
> 
> > Enter the message you would like to encrypt...
>
> Enter Your Message Here

> > Here is your encrypted message:
> >
> > Ktzkx Euax Skyygmk Nkxk
 

### Symbol Cipher:
> $ node message-mixer.js symbol
> 
> > Enter the message you would like to encrypt...
> 
> Enter Your Message Here

> > Here is your encrypted message:
> >
> > 3nt3r y0ur m3$$@g3 h3r3 

### Reverse Cipher: 
> $ node message-mixer.js reverse
> 
> > Enter the message you would like to encrypt...
> 
> Enter Your Message Here

> > Here is your encrypted message:
> > 
> > retnE ruoY egasseM ereH

### Super-Encoder:
> $ node super-encoder.js encode
> 
> > Enter the message you would like to encrypt...
> 
> hello world
> > $pp!1 hpv$@

> $ node super-encoder.js decode
> 
> > Enter the message you would like to encrypt...
> 
> $pp!1 hpv$@
> 
> > hello world
