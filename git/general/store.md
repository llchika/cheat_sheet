# Save mail, username and token
## Username
To store the username
```c
git config --global user.name 'username'
```

## Mail
To store the mail
```c
git config --global user.email 'email'
```

## Token
To store a token (warning the token will be saved locally in plaintext)
```c
git config --global credential.helper store
```
and then
```c
git push
```