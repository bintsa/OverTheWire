# OverTheWire
#---Level 0---

ssh bandit0@bandit.labs.overthewire.org -p 2220
bandit0@bandit.labs.overthewire.org's password: 'bandit0'
ls : readme 
cat readme : NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL

---Level 1--- 
-ssh bandit1@bandit.labs.overthewire.org -p 2220
-bandit1@bandit.labs.overthewire.org's password: NH2SXQwcBdpmTEzi3bvBHMM9H66vVXjL
-ls : - 
-cat ./- : rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi

---Level2---
-ssh bandit2@bandit.labs.overthewire.org -p 2220
-bandit2@bandit.labs.overthewire.org's password: rRGizSaX8Mk1RTb1CNQoXTcYZWU6lgzi
-ls : spaces in this filename 
-cat "spaces in this filename" : aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG


---Level 3---
-ssh bandit3@bandit.labs.overthewire.org -p 2220
-bandit3@bandit.labs.overthewire.org's password: aBZ0W5EmUfAf7kHTQeOwd8bauFJ2lAiG
-ls : inhere 
-cd inhere/ > ls -al
-cat ./.hidden : 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe

---Level 4---
-ssh bandit4@bandit.labs.overthewire.org -p 2220
-bandit4@bandit.labs.overthewire.org's password: 2EW7BBsr6aMMoJ2HjW067dm8EgX26xNe
-ls -al  
-cd inhere/ > ls -al 
-file ./-* 
-cat ./-file07 : lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR

---Level 5---
-ssh bandit5@bandit.labs.overthewire.org -p 2220
-bandit5@bandit.labs.overthewire.org's password: lrIWWI6bB37kxfiCQZqUdOIYfr6eEeqR
-ls -al 
-cd inhere/ > ls -al > find -type f -size 1033c 
-cat .maybehere07/.file2 : P4L4vucdmLnm8I7V17jG1ApGSfjYKqJU

---Level 6---
-ssh bandit6@bandit.labs.overthewire.org -p 2220
-bandit6@bandit.labs.overthewire.org's password: P4L4vucdmLnm8I7V17jG1ApGSfjYKqJU
-man find > find / -user bandit7 -group bandit6 -size 33c 2>/dev/null 
-cat /var/lib/dpkg/info/bandit7.password : mdp_bandit7

---Level 7---
-ssh bandit7@bandit.labs.overthewire.org -p 2220
-bandit7@bandit.labs.overthewire.org's password: z7WtoNQU2XfjmMtWA8u5rN4vzqu4v99S
-man grep 
-grep -n millionth ./data.txt  
-8994:millionth  TESKZC0XvTetK0S9xNwm25STk5iWrBvP

---Level 8---
-ssh bandit8@bandit.labs.overthewire.org -p 2220
-bandit8@bandit.labs.overthewire.org's password: TESKZC0XvTetK0S9xNwm25STk5iWrBvP
-cat data.txt | sort | uniq -u 
-EN632PlfYiZbn3PhVK3XOGSlNInNE00t

---Level 9---
-ssh bandit9@bandit.labs.overthewire.org -p 2220
-bandit9@bandit.labs.overthewire.org's password: EN632PlfYiZbn3PhVK3XOGSlNInNE00t
-strings data.txt | grep "=="
4========== the#
========== password
========== is
========== G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s

---Level 10---
-ssh bandit10@bandit.labs.overthewire.org -p 2220
-bandit10@bandit.labs.overthewire.org's password: G7w8LIi6J3kTb8A7j9LgrywtEUlyyp6s
-cat data.txt
-VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg==
-echo VGhlIHBhc3N3b3JkIGlzIDZ6UGV6aUxkUjJSS05kTllGTmI2blZDS3pwaGxYSEJNCg== | base64 --decode
-The password is 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM

---Level 11---
-ssh bandit11@bandit.labs.overthewire.org -p 2220
-bandit11@bandit.labs.overthewire.org's password: 6zPeziLdR2RKNdNYFNb6nVCKzphlXHBM
-cat data.txt | tr ‘A-Za-z’ ‘N-ZA-Mn-za-m’
-The password is JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv

---Level 12---
-ssh bandit12bandit.labs.overthewire.org -p 2220
-bandit12@bandit.labs.overthewire.org's password: JVNBBFSmZwKKOP0XbFXOoW8chDz5yVRv
-ls
-mkdir /tmp/fabiano
-cd /tmp/fabiano
-cp ~/data.txt .
-ls
-cat data.txt
-xxd -r data.txt > data.gz
-file data.gz
-gzip -d data.gz
-ls
-file data
-bzip2 -d data
-ls
-file data.out
-mv data.out data4.gz
-gzip -d data4.gz
-ls
-file data4
-tar xvf data4
-file data5.bin
-tar xfv data5.bin
-file data6.bin
-bzip2 -d data6.bin
-tar xfv data6.bin.out
-file data8.bin
-mv data8.bin data8.gz
-gzip -d data8.gz
-file data8
-cat data8 The password is: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw

---Level 13---
-ssh bandit13@bandit.labs.overthewire.org -p 2220
-bandit13@bandit.labs.overthewire.org's password: wbWdlBxEir4CaE8LaPhauuOo6pwRmrDw
-cat /etc/bandit_pass/bandit14
-fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq

---Level 14---
-ssh bandit14@bandit.labs.overthewire.org -p 2220
-bandit14@bandit.labs.overthewire.org's password: fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq
-echo "fGrHPx402xGC7U7rXKDaxiWFTOiF0ENq" | nc(netcat) localhost 30000
-Correct!
-jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt

---Level 15---
-ssh bandit15@bandit.labs.overthewire.org -p 2220
-bandit15@bandit.labs.overthewire.org's password: jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt
-cat /etc/bandit_pass/bandit14
-jN2kgmIXJ6fShzhT2avhotn4Zcka6tnt
-Correct!
-JQttfApK4SeyHwDlI9SXGR50qclOAil1

Level 16---
-ssh bandit16@bandit.labs.overthewire.org -p 2220
-bandit16@bandit.labs.overthewire.org's password: JQttfApK4SeyHwDlI9SXGR50qclOAil1

