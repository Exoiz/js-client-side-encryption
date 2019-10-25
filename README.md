# How to use

## 1. Encrypt

| Field                | Description                                                             |
| -------------------- | ----------------------------------------------------------------------- |
| String               | String you wish to encrypt e.g. "My secret recipe - Butter and Sugar".  |
| Password		       | Password to encrypt the string with e.g. "mysecretpassword".            |
| Key 				   | Additional key to encrypt the string with e.g. "RecipeSecret1".         |
| Reference (optional) | Reference e.g. "Kitchen".   									         |

## 2. Decrypt

| Field                | Description                                                             |
| -------------------- | ----------------------------------------------------------------------- |
| Encrypted string     | Encrypted string in base-64 e.g. "rCopuE0rvu4gLrAt0X36If0q8PiLnBZ1...". |
| Length               | Unencrypted string length e.g. "35".                                    |
| IV                   | Initialization vector used for added uniqueness e.g. "c83e762c1824...". |

## 3. Other

| Field                | Description                                                             |
| -------------------- | ----------------------------------------------------------------------- |
| URI Encoded string   | A string that can be added to the end of index.html to populate fields. |
| Decrypted string     | Output based on Encrypted string, Length, IV, Key1 and Key2.            |

