## GoldenCompany

[![Codacy Badge](https://api.codacy.com/project/badge/Grade/24c93c0d10d340d3b6876f74538ef5b5)](https://app.codacy.com/manual/lucasluizss/GoldenCompany?utm_source=github.com&utm_medium=referral&utm_content=lucasluizss/GoldenCompany&utm_campaign=Badge_Grade_Dashboard)

Nuget Packages

- ## Cryptography

For use Cryptography, you must import GoldenCompany and set value key.
Sample:

```csharp
public void YourMethod()
{

    Cryptography.SetKey("your-key")

    var password = "Abcdefgh@12345";

    var passwordEncrypted = Cryptography.Encrypt(password);

    var passwordDecrypted = Cryptography.Decrypt(passwordEncrypted);

}
```