# 1_Display_Output        

Η Python είναι μια πολύ απλή γλώσσα και έχει πολύ απλή σύνταξη. Ενθαρρύνει τους προγραμματιστές να προγραμματίζουν χωρίς ετοιμo κώδικα. Η απλούστερη οδηγία στην Python είναι η οδηγία "print" - απλά εκτυπώνει μια γραμμή (και περιλαμβάνει επίσης μια νέα γραμμή, αντίθετα με την C).

Υπάρχουν δύο μεγάλες εκδόσεις Python, Python 2 και Python 3. Οι Python 2 και 3 είναι αρκετά διαφορετικές. Αυτό το course χρησιμοποιεί το Python 3, επειδή είναι πιο σωστό και υποστηρίζει νεότερες λειτουργίες. Για παράδειγμα, μία διαφορά μεταξύ των Python 2 και 3 είναι η δήλωση εκτύπωσης. Στην Python 2, η δήλωση "print" δεν είναι μια συνάρτηση και ως εκ τούτου χρησιμοποιείται χωρίς παρενθέσεις. Ωστόσο, στην Python 3, είναι μια συνάρτηση και πρέπει να γίνεται με παρενθέσεις.

Για να εκτυπώσετε μια συμβολοσειρά στο Python 3, γράψτε απλά:

```python
print("Καλημέρα Κόσμε !!!")
```
Output:
```
>>> Καλημέρα Κόσμε !!!
```

Επίσης μπορούμε να χρησημοποιήσουμε και " " και ' ' , το αποτέλεσμα θα είναι το ίδιο στην εκτύπωση. Η μόνη διαφορα ειναι οτι στα μεν μπορεις να   γραψεις μεσα με ' και στα δε μπορεις να γραψειος μεσα και ".

```python
print("Καλημέρα' Κόσμε !!!")
print('Καλημέρα" Κόσμε !!!')
```
Output:
```
>>> Καλημέρα' Κόσμε !!!
>>> Καλημέρα" Κόσμε !!!
```

Τέλος αν θέλουμε μέσα στο κείμενο μπορούμε να γραφουμε " και ' τοτε βάζουμε το κείμενο μεσα σε τριπλα, δηλαδή ''' η """.

```python
print("""Καλημέρα ' " Κόσμε !!!""")
print('''Καλημέρα " ' Κόσμε !!!''')
```
Output:
```
>>> Καλημέρα ' " Κόσμε !!!
>>> Καλημέρα " ' Κόσμε !!!
```