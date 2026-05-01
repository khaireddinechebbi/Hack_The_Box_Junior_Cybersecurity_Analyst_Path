## Directory Indexing
Keep in mind the key WordPress directories discussed in the WordPress Structure section. Manually enumerate the target for any directories whose contents can be listed. Browse these directories and locate a flag with the file name flag.txt and submit its contents as the answer.
```bash
HTB{3num3r4t10n_15_k3y}
```

## User Enumeration
From the last cURL command, what user name is assigned to User ID 2?
```bash
ch4p
```

## Login
Search for "WordPress xmlrpc attacks" and find out how to use it to execute all method calls. Enter the number of possible method calls of your target as the answer.
```bash
80
```

## WPScan Enumeration
Enumerate the provided WordPress instance for all installed plugins. Perform a scan with WPScan against the target and submit the version of the vulnerable plugin named “photo-gallery”.
```bash
1.5.34
```

## Exploiting a Vulnerable Plugin
Use the same LFI vulnerability against your target and read the contents of the "/etc/passwd" file. Locate the only non-root user on the system with a login shell.
```bash
sally.jones
```

## Attacking WordPress Users
Perform a bruteforce attack against the user "roger" on your target with the wordlist "rockyou.txt". Submit the user's password as the answer.
```bash
lizard
```
