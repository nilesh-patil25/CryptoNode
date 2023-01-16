# CryptoLibrary


For adding reference of this project first you need to add NETStandard.Library in your project.
You can use following command to add that
> dotnet add package NETStandard.Library --version 2.0.3

After adding you add this dll in your project
## Choose an algorithm

You can select an algorithm for different reasons:
for example, for data integrity, for data privacy, or to generate a key.
Symmetric and hash algorithms are intended for protecting data for either integrity reasons 
(protect from change) or privacy reasons (protect from viewing). Hash algorithms are used primarily for data integrity.

### Here is a list of recommended algorithms by application:

- Data privacy:
   - Aes
- Data integrity:
    - HMACSHA256
    - HMACSHA512

- Digital signature:
    - ECDsa
    - RSA
- Key exchange:
    - ECDiffieHellman
    - RSA
- Random number generation:
    - RandomNumberGenerator.Create
- Generating a key from a password:
    - Rfc2898DeriveBytes
