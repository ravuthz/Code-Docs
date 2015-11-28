Security Functions
==================

encode_password($password, $salt = null)
----------------------------------------
    * $password : Password or any secure text to encrypt
    * $salt : Character to combine with password to encrypt or decrypt, when $salt is empty or null this will get the encryption=key from the default config.

decode_password($passcode, $salt = null)
----------------------------------------
    * $passcode : Encrypted password to decrypt.
    * $salt : Character to combine with password to encrypt or decrypt, when $salt is empty or null this will get the encryption_key from the default config.
