# Phase 01 : BASIC Reconocence

In This  phase , we learn about Basic things,

1. Advance Search on google
2. Find Active Ports on a website.
3. Social Engineering for find  person 
4. SSH & SCP [Remote Connection & File transfer]
---

# TOPICS:

<details>

<summary>  ADVANCE SEARCH  </summary>

# Advance Searching 

I started looking for a website, how hackers lookup it. some google advance key features make this lookup even far better.

ex: If I looking for an pdf of a book, i simply search it on google but in advance search I search it like this:

```
site:google.com filetype:pdf "Book Name"
```

```html
site:google.com filetype:pdf Penetration Testing Paperback
```

![Rec-01](/Image/Phase_01/rec01.png)

</details>

<details>

<summary>  FINDING PORTS</summary>

# How  to find  active ports on a website : 

we know that , every website has  a port that allows a user to Enter the website, port is like a door of a website.. common ports like :  

>  Port 80 (HTTP), 443 (HTTPS), 21 (FTP), 22 (FTP share)  

IN Kali their are Several tools that allows user to know the ports and other stuffs like  :

> dig, nslookup

- How to  use it :
    - just type dig <domain name/ip> [name of the operation]
    - > i.g. dig google.com ns

Here ns is name server (ns)

some list of dig tools showed below : 

![img dig tool](/Image/Phase_01/DIG.png)

</details>

<details><summary> SOCIAL ENGINEERING</summary> 

# SOCIAL ENGINEERING 

---

Social engnieering is a method that use for tweaks person and steal their personal details.

In Kali Linux their is a tools that is help for find out a person's all social media information.

## pros :

- Easy to find out all the details in  minutes.

## Cons:

- If username is different then it might show other person's info who has this username.

---

### Tools Uses : 

```
sherlock <username> 
```

Results :

![Image Example](/Image/Phase_01/SL.png)

##### MORE DETIALS  WILL BE ADDED IN SOON...........

</details>

<details><summary>SSH & SCP</summary>
 
 [[SSH & SCP]----> click here](https://github.com/pran0x/MY-CYBER-JOURNEY/blob/9a52c40243f6b78f54676a707c5349ade6b657a8/ssh&scp/readme.md)

</details>

---

[<< Go Back](https://github.com/pran0x/MY-CYBER-JOURNEY/blob/bdd07c2edb033502c8c445de575178e8f845f585/README.md)



                                            HAPPY HACKING 
                                            



                            ____ _______      ____  ___________________ 
                          / __ \/ ____/ |  / / __ \/ /| |  / /____/ ___\\
                         / /_/ / __/  | | / / / / / / | | / / __/ / /_/ /
                        / _, _/ /___  | |/ / /_/ / /__| |/ / /___/ _, _/  
                       /_/ |_/_____/  |___/\____/_____/___/_____/_/ |_|   
                                    Written By ROOT~REVOLVER