# Labor 05-06
# Gyakori elemhalmazok előállítása
A gyakori elemhalmazok keresése elvileg az elemhalmazháló bejárásaként is tekinthető. A bejárás komplexitása exponenciális.

## Apriori-elv
Ha egy elemhalmaz gyakori, akkor ezen elemhalmaz összes részhalmaza is gyakori. Az apriori-elv alkalmazásával a részhalmazok exponenciális keresési tere csökkenthető.

## Apriori algoritmus
A laborgyakorlatban az apriori algoritmus Python implmentációját próbáljuk ki.

Az Apriori algoritmus a legismertebb gyakori elemhalmaz keresésére alkalmas módszer. Szélességi bejárást valósít meg: az üres halmazból kiindulva szintenként halad előre a nagyobb méretű gyakori elemhalmazok meghatározásához. Minden iterációban az eggyel nagyobb méretű elemhalmazokkal foglalkozik, így az iterációk száma legfeljebb eggyel több, mint a legnagyobb gyakori elemhalmaz mérete.

# Feladatok
1. Nyissuk meg Colabban a laborhoz tartozó `.ipynb` notebook fájt, oldjuk meg a feladatokat. A laboróra végén ne felejtsük el visszamenteni a szerkesztett jegyzetfüzetet a GitHubra.
