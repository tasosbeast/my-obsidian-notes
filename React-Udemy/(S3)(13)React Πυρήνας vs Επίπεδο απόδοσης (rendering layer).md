
Όταν χρησιμοποιούμε τη [[React]] μέσω `<script>` tags (χωρίς [[bundlers]]), φορτώνονται δύο ξεχωριστές [[libraries|βιβλιοθήκες]]:

---

### 1. **[[React]] Core Library**

```html
<script src="https://unpkg.com/react@18/umd/react.development.js"></script>
```

Αυτή περιλαμβάνει τη **βασική λειτουργικότητα** της [[React]]:

- Δημιουργία [[components]]
    
- Υποστήριξη [[hooks]] όπως `useState`, `useEffect` [[useState]] [[useEffect]]
    
- Διαχείριση [[state]]
    
- Η εσωτερική [[reactive]] λογική rendering
    

Ουσιαστικά, ορίζει **πώς λειτουργεί μια εφαρμογή React εσωτερικά**.

---

### 2. **React DOM (Rendering Layer)**

```html
<script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
```

Αυτή η βιβλιοθήκη παρέχει τη **μηχανή απόδοσης** (rendering engine) που συνδέει τη React με το [[DOM]].  
Επιτρέπει στα React [[components]] να αποδοθούν μέσα στη σελίδα — συνήθως σε ένα στοιχείο όπως το `[[id="root"]]`. [[(S3)(13)Το id=root είναι το προεπιλεγμένο σημείο σύνδεσης (mount point) στη React|id="root"]]

---

Η [[React]] είναι σχεδιασμένη να είναι **platform-agnostic** (δηλαδή δεν εξαρτάται από το πού γίνεται rendering). Το `react-dom` είναι η βιβλιοθήκη που χρησιμοποιεί η [[React]] για να αποδίδει τα [[components]] μέσα στο [[DOM]], δηλαδή **στο περιβάλλον του browser**., ενώ άλλοι όπως το `react-native` χρησιμοποιούνται για mobile εφαρμογές.