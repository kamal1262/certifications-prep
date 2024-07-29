- KMS key be delete but there is a waiting perioud onf 7 days to 30 days 
- during this 7-30 days, KMS key be not be used to descrypted it

Astmettric key encryption: 
- data is encrypted with one key (public) and decrypt with another key (Private)  
- Asymetric keys with KMS
-  Digital signing with KMS 
- Data key caching : reusing same key to encrypt multiple keys 
    - when you need a key to encrypt or decrypt data, you can reuse a data key from cache instead of creating a new key 
    - if is preferred to use data key caching when high frequnecy of KMS key and latenhc/slow master key operation 