[![Python](https://img.shields.io/badge/Python-3.7-orange)](https://www.python.org/downloads/release/python-2716/)
[![Run on Repl.it](https://repl.it/badge/github/athamour1/DisplayOutput)](https://repl.it/)

# 4_Performing_Calculations

Στην python μπορούμε να εκτελέσουμε αριθμιτικές πράξεις με βάση τους τελεστές απο το παρακάτω πινακάκι:

|Συμβολο|Λειτουργία        |Χρηση     |
|:-----:|------------------|----------|
|+      |Προσθαιση         |Z = x + y |
|-      |Αφαιρεση          |Z = x - y |
|*      |Πολλαπλασιασμος   |Z = x * y |
|**     |Υψωση σε δύναμη   |Z = x ** y|
|/      |Διαίρεση          |Z = x + y |
|//     |Ακέραια διαίρεση  |Z = x // y|
|%      |Υπόλοιπο διαίρεσης|Z = x % y |

Μερικα παραδήγματα απο το temrinal:

## Πρόσθεση-Αφαίρεση

```python
>>> x=5
>>> y=2
>>> x+y
7
```

```python
>>> x=5
>>> y=2
>>> x-y
3
```

### Ασκηση

- Γράψτε ένα προγραμμα που να βγαζει το σύνολο των χρημάτων που χαλας της εβδομάδα.
    <details><summary>Απάντηση</summary>
    <p>

    ```python
    sum = 0
    for x in range(7):
        sum = sum + int(input('ημέρα ' + str(x+1) + 'η '))
    print('το sum ειναι: ' + str(sum) + ' euro')
    ```

    </p>
    </details>
    

## Διαίρεση-Ακέραια διαίρεση-Υπόλοιπο διαίρεσης

```python
>>> x=5
>>> y=2
>>> x/y
2.5
```

```python
>>> x=5
>>> y=2
>>> x//y
2
```

```python
>>> x=5
>>> y=2
>>> x%y
1
```

### Ασκηση

- Γράψτε ένα προγραμμα που να βγαζει το σύνολο των χρημάτων που χαλας της εβδομάδα και τον μεσο όρο ανά μέρα.
    <details><summary>Απάντηση</summary>
    <p>

    ```python
    sum = 0
    for x in range(7):
        sum = sum + int(input('ημέρα ' + str(x+1) + 'η '))
    mo = sum/7
    print('το sum ειναι: ' + str(sum) + ' euro')
    print('Ο Μεσος Όρος ανα μέρα ειναι: ' + str(mo) + ' euro')
    ```

    </p>
    </details>

## Πολλαπλασιασμος-Υψωση σε δύναμη 

```python
>>> x=5
>>> y=2
>>> x*y
10
```

```python
>>> x=5
>>> y=2
>>> x**y
25
```

### Ασκηση

- Γράψτε ένα προγραμμα που να βγαζει το τετράγωνο ενός αριθμού για παντα. Και θα πρεπει να εχει την ακόλουθη δομη μεχρι να τερματήσει ο χρηστης το πρόγραμμα.

    ```bash
    $ Δωσε αριθμό 
    $ Το τετράγωνο του αριθμού x ειναι:
    $ Θελετε να συνεχήσετε? Y/N (yes or no): 
    ```
    <details><summary>Απάντηση</summary>
    <p>

    ```python
    log=True
    while log:
        x = int(input('Δωσε αριθμό'))
        z = x**2
        print('Το τετράγωνο του αριθμού ' + str(x) + ' ειναι το : ' + str(z))
        y = input('Θελετε να συνεχiσετε? Y/N (yes or no):')
        while not(y='Y' or y='N'): # για να ημαστε σιγουροι οτι δεν εβαλε κατι αλλο
            y = input('Θελετε να συνεχήσετε? Y/N (yes or no):')
        if y = 'N':
            log=Fasle       
    ```

    </p>
    </details>