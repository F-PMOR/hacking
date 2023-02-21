# hashcat

## site web
https://hashcat.net/hashcat/

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

### LM hash crack
hashcat -a 0 -m 3000  hash.txt dict/rockyou.txt -d 1 -o out.txt --show

## dictionnaires 

- rockyou : https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwi04brRrqf9AhXGUKQEHbPxAUgQFnoECBwQAQ&url=https%3A%2F%2Fgithub.com%2Fbrannondorsey%2Fnaive-hashcat%2Freleases%2Fdownload%2Fdata%2Frockyou.txt&usg=AOvVaw3snAERl1mU6Ccr4WFEazBd



