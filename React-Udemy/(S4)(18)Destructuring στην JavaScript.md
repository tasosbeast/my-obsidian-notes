
### 🧩 **Destructuring** στη [[JavaScript]]

Το **Destructuring** είναι ένα χαρακτηριστικό της [[JavaScript]] που επιτρέπει στους developers να **εξάγουν values από [[objects]] ή [[arrays]]** σε ξεχωριστά variables με συνοπτικό τρόπο.

---

### 🔧 Object Destructuring

Χρησιμοποιείται για να εξάγουμε ιδιότητες από ένα [[object]] με βάση τα ονόματα των properties.

```js
const book = getBook(2); // παράδειγμα object

// Παραδοσιακά:
const title = book.title;
const author = book.author;

// Με destructuring:
const { title, author } = book;
```

⚠️ Τα ονόματα των μεταβλητών **πρέπει να ταιριάζουν ακριβώς** με τα property names του object. Αν γράψεις `titles` αντί για `title`, θα πάρεις `undefined`.

Το object destructuring είναι ιδιαίτερα χρήσιμο όταν:

- Θέλεις να έχεις πρόσβαση σε πολλές ιδιότητες ενός object
    
- Εργάζεσαι με απαντήσεις από [[APIs|API]] (π.χ. `getBook()`)
    

Μπορείς να εξάγεις και περισσότερες ιδιότητες ταυτόχρονα:

```js
const { title, author, pages, publicationDate, genres, hasMovieAdaptation } = book;
```

---

### 🔧 Array Destructuring

Χρησιμοποιείται για να εξάγεις τιμές με βάση τη **θέση** τους μέσα σε ένα [[array]] (και όχι το όνομα).

```js
const genres = book.genres;

// Παραδοσιακά:
const primaryGenre = genres[0];
const secondaryGenre = genres[1];

// Με destructuring:
const [primaryGenre, secondaryGenre] = genres;
```

Χρήσιμο όταν:

- Η σειρά των στοιχείων έχει σημασία (π.χ. ταξινομημένα [[data]])
    
- Θέλεις μόνο τα πρώτα 1–2 στοιχεία του array
    

---

### 🛠 Εργαλεία που αναφέρθηκαν

- **[[Quokka.js]]**: Extension για το [[VS Code]] που επιτρέπει να τρέχεις [[JavaScript]] inline, χωρίς να χρειάζεσαι [[HTML]] αρχείο.
    
- **[[Snippets]]**: Κομμάτια επαναχρησιμοποιούμενου κώδικα — π.χ. για γρήγορο `console.log()`
    

---

### ✅ Σύνοψη

Το **destructuring** είναι καθαρή και ισχυρή σύνταξη στη [[JavaScript]], η οποία βελτιώνει τη [[readability|αναγνωσιμότητα]] του κώδικα και μειώνει τον επαναλαμβανόμενο κώδικα.  
Χρησιμοποιείται συχνά όταν χειριζόμαστε [[objects]] από [[functions]], [[APIs]] ή μεγάλα [[arrays]].

---

Θες να το μετατρέψουμε και σε πλήρες markdown αρχείο έτοιμο για το vault σου;