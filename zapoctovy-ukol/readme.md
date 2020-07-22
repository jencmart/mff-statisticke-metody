## Nejaky predesly ukol na stejnych datec:
* Zkuste do R načíst data police.txt (pomocí příkazu read.table()) a podívejte se na výstup příkazů 

```
model1 <- lm(react~height*weight+pulse,data=police);
print(model1); 
summary(model1)
```

* Rozmyslete si přitom význam jednotlivých čísel v počítačovém výstupu (hvězdička v příkazu `lm()` přidá do modelu i interakci váhy a výšky). 

* Grafy různých typů reziduí (a dalších charakteristik) snadno získáte použitím príkazu plot(model1).



## Zadání zápočtového úkolu:

* Podle 12.3  model ktery nejlepe vysvetluje reakční dobu (transformace proměnných + jejich interakce)


* Které vysvětlující proměnné mají statisticky signifikantní vliv na reakční dobu?
* Jaká je interpretace jednotlivých regresních koeficientů? 
* Co znamenají čísla uvedená v počítačovém výstupu?


* Na základě grafů reziduí (v R: plot(lm(....))) 
* a vypočtených charakteristik pro detekci vlivných pozorování (v R: influence.measures(...)) 
* najděte pozdezřelá (vlivná nebo odlehlá) pozorování 
* a okomentujte splnění (nebo nesplnění) jednotlivých předpokladů lineárního regresního modelu.

