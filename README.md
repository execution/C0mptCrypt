<h1 align="center">
	<img src="https://www.nicepng.com/png/full/395-3955868_security-shield-lock-icon.png" width="150px"><br>
    C0mptCrypt - An object-oriented, minamalistic, simple encryption library in Python.
</h1>
<p align="center">
    C0mptCrypt allows you to encrypt strings of text, and decrypt that text. It can only be decrypted using C0mptCrypt and not by random online tools. You can use this for a variety of things from creating passwords, to encrypting HWIDs and much more!.
</p>

<h1></h1>

**Install**

```
pip install git+https://github.com/execution/C0mptCrypt
```

<h1></h1>

**Code Example**

```python
from C0mptCrypt import C0mptCrypt

string = input("Enter string: ")

enc = C0mptCrypt().Encrypt(string)

print(enc)
```

```python
from C0mptCrypt import C0mptCrypt

string = input("Enter encrypted string: ")

enc = C0mptCrypt().Decrypt(string)

print(enc)
```
