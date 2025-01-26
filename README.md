# rvque9-mobdev

# KotlinShoppingList alkalmazás módosítása
***Bartók Péter László RVQUE9***

***III. évfolyam*** 

***Mérnökinformatikus, levelező***

---

1. [KotlinShoppingList alkalmazás módosítása](#kotlinshoppinglist-alkalmazás-módosítása)
   1. [Csomagnevek és tartalmazó mappa módosítása](#csomagnevek-és-tartalmazó-mappa-módosítása)
   2. [Háttérkép módosítása](#háttérkép-módosítása)
   3. [A háttér színének módosítása](#a-háttér-színének-módosítása)
   4. [Az új költségtípus hozzáadásánál a plain text szöveg megváltoztatása](#az-új-költségtípus-hozzáadásánál-a-plain-text-szöveg-megváltoztatása)
   5. [Adatbázis név és adattartalom módosítás](#adatbázis-név-és-adattartalom-módosítás)
   6. [Költséghozzáadó ikon változtatása](#költséghozzáadó-ikon-változtatása)
   7. [Költségtételt jelző címkék megváltoztatása](#költségtételt-jelző-címkék-megváltoztatása)

---


## Csomagnevek és tartalmazó mappa módosítása

Az alkalmazásban először a csomagneveket és a tartalmazó mappa nevét módosítottam, a KotlinShoppinglist alkalmazást átneveztem VasarlasiLista névre.

---

## Háttérkép módosítása

A következő lépés az alkalmazás felső részében található kép módosítása volt.
![Költségnyilvántartó képe](images/activiti_main.jpg)

A képet a következő helyre kellett bemásolni, hogy megtörténhessen a módosítás:

```
CostAccountant\app\src\main\res\drawable
```

A változtatást az activity_main.xml fájlban kellett végrehajtani. A folyamatot a következő kép szemlélteti:

![Kép módosítás](images/Modify_background_pictures.jpg)

---

## A háttér színének módosítása

A kép alatt található rész háttérszínét kékre változtattam, szintén az activity_main.xml fájlban, ahogy a következő ábra mutatja:

![Háttérkép változtatása](img/hatterszin_valtoztat.png)

Ezzel a lehetőséggel az alapértelmezetten elérhető színek között választhatunk. Csak  teszt kedvéért választottam a sárgát.

---

## Az új költségtípus hozzáadásánál a plain text szöveg megváltoztatása

Az új kiadás bevitelére szolgáló plain textek alapértelmezett szövegét magyar nyelvűre változtattam, dőlt betűvel látható. Sorrendben a következők lettek:
* Termék neve - vásárlás értéke
* Darabszám
* Ár
* Bolt
* Illetve egy kész gombot is beszúrtam.

![Szöveg változtatása](img/szoveg_valtoztat.png)

Az Darabszám adattípusnak decimal lett.

![Adattípus változtatása](img/adattipus_valtoztat.png)

---

## Adatbáz tábla átnevezése és az Adatbázisban a tábla nevének módosítása
Az adatbázis neve az AppDatabase-en belül shopping.db-ről termek.db-re válozott.

![Adattípus változtatás2](img/adattipus_valtoztat2.png)

---

## Költséghozzáadó ikon változtatása

Az ikont a levél ikonról pipa jelre változtattam és megcseréltem a háttér színét is. jelre változtattam.

![Ikon változtatás](img/ikon_valtoztat.png)

---

## Költségtételt jelző címkék megváltoztatása

A változtatásokat a row_item.xml fájlban kell elvégezni. A feliratok szövege és címe mellett más lett a háttér és szövegek színe is.

![Címkék változtatása](img/cimke_valtoztat.png)


---
