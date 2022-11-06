# ****Testové zadání - práce se soubory v Pythonu****


## Úkol č. 1

### **Pokyny k vypracování:**

Složka obsahuje níže uvedené soubory:
* ***1.txt***
* ***2.txt***
* ***3.txt***

Je potřeba je spojit do jednoho souboru s názvem merget_files.txt dle následujících požadavků:

1. sloučení souborů by mělo být realizováno prostřednictvím Pythonu,
2. pořadí zápisu do souboru merged_files.txt určuje počet řádků v jednotlivých souborech (tzn. soubor s nejmenším počtem řádků by měl být do finálního souboru zapsán jako první a soubor s největším počtem řádků jako poslední),
3. při sloučení souboru vždy uveďte jeho název a počet řádků.


### **Finální soubor merget_files.txt by měl vypadat následovně:**

```
3.txt
3
Beautiful is better than ugly.
Explicit is better than implicit.

1.txt
6
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.

2.txt
11
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those! 
```


## Bonusový úkol - requests (\*nepovinný)
Nejdůležitější web pro programátory je [stackoverflow](https://stackoverflow.com/), který má veřejné [API](https://api.stackexchange.com/docs). 
Je třeba napsat program, jehož výstupem bude seznam otázek s tagem 'Python', za poslední dva dny.
Tato úloha nevyžaduje token.

### **Příklad výstupu**
```
Otázka číslo: 1; 2022-11-05 16:59:09
['python', 'search', 'artificial-intelligence', 'breadth-first-search']
Implementation of Breadth First Search for solving Puzzle
https://stackoverflow.com/questions/74329743/implementation-of-breadth-first-search-for-solving-puzzle

Otázka číslo: 2; 2022-11-05 16:58:11
['python', 'list', 'numpy']
Load custom dataset of with multiple categories into training and testing sets?
https://stackoverflow.com/questions/74329731/load-custom-dataset-of-with-multiple-categories-into-training-and-testing-sets
...
```

### **Obecné informace k úkolům:**

1. inicializujte lokální Git repozitář na svém PC,
2. naklonujte si potřebné soubory z [GitHub](https://github.com/CSAS-TestoveZadani/Testove_zadani),
3. vytvořte veřejný repozitář na GitHubu a propojte ho s lokálním,
4. bonusový úkol není povinný :)
5. odkaz na GitHub s vypracovaným zadáním pošlete na email: ***EBannikova@csas.cz*** do středy ***09. 11. 2022***.
