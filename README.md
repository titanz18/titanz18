I use Split GPG in Qubes, with subkeys.

The key at https://conorz.tk/gpg is the one I use for email.
The fingerprint is:   
CF70 A92F 24B4 BF66 C61A  2034 65EC 4C53 D564 614F

*I have used this key to sign this note.*

I use a separate key for signing code:
```
pub   rsa4096 2023-03-17 [SC]
      5A3D 0715 FEDE C4AB 5853  D4AB 7A1A B350 7D9B 734F
uid           [ultimate] titanz (titanz repo signing key) <titanz@pm.me>
sub   rsa4096 2023-03-17 [E]
sub   rsa4096 2023-03-17 [S] [expires: 2024-03-16]
```
Both are available on keyservers - for example:   
https://keyserver.ubuntu.com/pks/lookup?search=titanz&fingerprint=on&op=index

The public key I use for repo signing is titanz.pub
gpg-keys.asc contains a PGP Signed copy of this information.