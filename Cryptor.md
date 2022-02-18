# Cryptor 
Cryptor is an encapsulated encryption/decryption based on 128bits-RSA algorithm
````
 	Cryptor (String k)
 	Basic constructor. More...
 
void 	setCryptoKey (String k)
 	Changes the key ot be used. More...
 
String 	getCryptoKey ()
 	Returns the embedded key. More...
 
String 	enCrypt (String text)
 	Encripts a String into another string by using a 128bits-RSA Algorithm and the embedded key. More...
 
String 	deCrypt (String text)
 	It tries to decrypt a string with the embedded key. More...
```` 
