# hashcat


## IMPORTANT
Il est possible de lancer hashcat (windows) à partir de wsl (donc  linux !!!).

```
pmorry@Alienware:cd /mnt/c/my programmes/hashcat-6.2.6
pmorry@Alienware:/mnt/c/my programmes/hashcat-6.2.6$ hashcat.exe -b -d 1
```

## site web
https://hashcat.net/hashcat/
* pages des attaques et hash_type : https://hashcat.net/wiki/doku.php?id=hashcat


## commandes
-b : benchmark (permet de voir les différents devices pris en charge - cpu, GPU... et leur numéro)  
-m : hash type  
-a : attaque mode  
-d 1: utilise le device #1 (voir -b)  
-o outputfile : fichier sortie hash:mdp  
--status : montre l'état d'avancement  
--show: montre les hash cracké (dans le fichier si -o utilisé)  

ex : hashcat -a 0 -m 3000  hash.txt dict/rockyou.txt -d 1 -o out.txt --show


### benchmark
hashcat -b 

### LM hash crack (à travers un dictionnaire)
hashcat -a 0 -m 3000  hash.txt dict/rockyou.txt -d 1 -o out.txt --show

### NT hash crack (Brut force avec increment des charset de 1 à 8) (?a = all, ?d = digit, ?l = lowercharset, ?u = uppercharset...)
```
hashcat -a 0 -m 1000 -i -d 1 -o out.txt --status hash.txt ?a?a?a?a?a?a?a?a
```
* via dictionnaire :
```
hashcat.exe -a 0 -m 1000 -d 1  -o NT.txt --status hash.txt dict/passwords.txt.gz
```
* NE PAS OUBLIER DE REGARDER LE FICHIER NT.txt QUI CONTIENDRA LES MDP CRACKE


## dictionnaires 

- rockyou : https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi04brRrqf9AhXGUKQEHbPxAUgQFnoECBwQAQ&url=https%3A%2F%2Fgithub.com%2Fbrannondorsey%2Fnaive-hashcat%2Freleases%2Fdownload%2Fdata%2Frockyou.txt&usg=AOvVaw3snAERl1mU6Ccr4WFEazBd



