# Over The Wire Linux Command Learning

ssh bandit(Level #)@bandit.labs.overthewire.org -p 2220

## Level 0 --> 1
Command(s) used: ```ls```, ```cat```

Password found: ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

## Level 1 --> 2
Command(s) used: ```cat ./(Special character filename)```

Password found: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

## Level 2 --> 3
Command(s) used: ```cat ./--spaces\ in\ this\ filename--```

Password found: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx

## Level 3 --> 4
Command(s) used: ```ls -a```, ```cat```

Password found: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ

## Level 4 --> 5
Command(s) used: ```find /dir/to/files/ -type f -exec file {} \; | grep text```

Password found: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw

## Level 5 --> 6
Command(s) used: ```find /dir/to/files/ -type f -size (File Size)c ! -executable```

Password found: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

## Level 6 --> 7
Command(s) used: ```find /. -size (File Size) -user (User Name) -group (Group Name) -exec ls -lh {} +```

Password found: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

## Level 7 --> 8
Command(s) used: ```grep -i "Your Word" (File Name)```

Password found: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

## Level 8 --> 9
Commands used: ```sort (File Name) | uniq -u```

Password found: 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

## Level 9 --> 10
Commands used: ```strings (File Name).txt | grep "="```

Password found: FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

## Level 10 --> 11
Commands used: ```echo "base64 encrypted string" | base64 --decode```

Password found: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

## Level 11 --> 12
Commands used: ```tr 'A-Za-z' 'N-ZA-Mn-za-m' < (File Name).txt```

Password found: 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

## Level 12 --> 13
Commands used: ```xxd -r (File).txt > (New File Name)```, ```file (New File Name)```, ```mv (New File Name) (New File Name).gz / gunzip (New File Name).gz```, ```mv (New File Name) (New File Name).bz2 / bunzip2 (New File Name).bz2```, ```tar -xf (New File Name)```

Password found: FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

## Level 13 --> 14
Commands used: ```chmod (Permissions) (File)```, ```ls -l (File)```

Password found: MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

## Level 14 --> 15
Commands used: ```echo "Password" | nc localhost 30000```

Password found: 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

## Level 15 --> 16
Commands used: ```openssl s_client -connect localhost:30001```

Password found: kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx

## Level 16 --> 17
Commands used: ```nmap -p 31000-32000 --script ssl-enum-ciphers localhost```, ```openssl s_client -connect localhost:(Port)```

Password found: SSH Key to get to level 17

## Level 17 --> 18
Commands used: ``` diff -y (File #1) (File #2)```

Password found: x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO

## Level 18 --> 19
Commands used: ```-t cat readme```

Password found: cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8

## Level 19 --> 20
Commands used: ```./(File) cat /path/to/password/ ```

Password found:0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO

## Level 20 --> 21
Commands used: ``` ```

Password found:

## Level 21 --> 22
Commands used: ``` ```

Password found:

## Level 22 --> 23
Commands used: ``` ```

Password found:

## Level 21 --> 22
Commands used: ``` ```

Password found:

## Level 21 --> 22
Commands used: ``` ```

Password found:

## Level 21 --> 22
Commands used: ``` ```

Password found:

## Level 21 --> 22
Commands used: ``` ```

Password found:
