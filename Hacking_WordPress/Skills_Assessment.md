# Scenario
You have been contracted to perform an external penetration test against the company INLANEFREIGHT that is hosting one of their main public-facing websites on WordPress.

Enumerate the target thoroughly using the skills learned in this module to find a variety of flags. Obtain shell access to the webserver to find the final flag.

## Question 1:
Identify the WordPress version number.
```bash
5.1.6
```

## Question 2:
Identify the WordPress theme in use.
```bash
twentynineteen
```

## Question 3:
Submit the contents of the flag file in the directory with directory listing enabled.
```bash
HTB{d1sabl3_d1r3ct0ry_l1st1ng!}
```

## Question 4:
Identify the only non-admin WordPress user.
```bash
Charlie Wiggins
```

## Question 5:
Use a vulnerable plugin to download a file containing a flag value via an unauthenticated file download.
```bash
HTB{unauTh_d0wn10ad!}
```

## Question 6:
What is the version number of the plugin vulnerable to an LFI?
```bash
1.1.1
```

## Question 7:
Use the LFI to identify a system user whose name starts with the letter "f".
```bash
frank.mclane
```

## Question 8:
Obtain a shell on the system and submit the contents of the flag in the /home/erika directory.
```bash
HTB{w0rdPr355_4SS3ssm3n7}
```
