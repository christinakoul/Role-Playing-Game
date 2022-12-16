# Lesson: Digital & Serious Games

### First and Last Name:  Κουλιοπούλου Χριστίνα
### University Registration Number: dpsd18052
### GitHub Personal Profile: https://github.com/christinakoul
### Digital & Serious Games Personal Repository: https://github.com/christinakoul/Role-Playing-Game

# Introduction
Το συγκεκριμένο έγγραφο αποτελεί την πρώτη αναφορά της εξαμηνιαίας εργασίας
της Κουλιοπούλου χριστίνας(dpsd18052) στα πλαίσια του μαθήματος Ψηφιακά
Παιχνίδια και Παιγνιώδης Μάθηση των διδάσκοντα Αλέξανδρος Μερκούρης για το
χειμερινό εξάμηνο.
Σκοπός της εργασίας είναι η δημιουργία ενός 2D παιχνιδιού RPG. Το παιχνίδι δεν
δημιουργείται από την αρχή αλλά γίνεται fork απο το κεντρικό αποθετήριο του
παιχνιδιού και εργαζόμαστε πάνω στον αρχικό κώδικα για περαιτέρω αλλαγές και
τροποποιήσεις.

# Summary
Η διαδικασία που ακολούθησα είναι η εξής:
Αρχικά ακολούθησα τις οδηγίες του πρώτου παραδοτέου και έκανα όλα τα βήματα
για τον χαρακτήρα της Ruby, έκανα scene, έφτιαξα τους φακέλους για τα sprites και
πρόσθεσα την ruby. Μετά έκανα τον κώδικα για το script για κάθετη και οριζόντια
κινηση στον χώρο. Έπειτα με χρήση των tilemaps έβαλα το αρχικό πλακάκι του
παιχνιδιού της Ruby, και στη συνέχεια προσθεσα στα sprites τα δικά μου assets
ώστε να φτιάξω το παιχνίδι μου. Οπότε άλλαξα τον χαρακτήρα σε μάγισσα και
διακόσμησα τον χώρο του παιχνιδιού με την μωβ πίστα ενώνοντας τα διαφορα
πλακάκια. Τέλος έδωσα κίνηση στον χαρακτήρα μου όπως είχαμε μάθει στο
εργαστηριακό μάθημα.

# 1st Deliverable
Το πρώτο παραδοτέο, αφορά τον αρχικό σχεδιασμό της εφαρμογής. Ο σχεδιασμός
ακολουθεί τις οδηγίες που έχουν δοθεί γραπτώς στο GitHub. Πιο συγκεκριμένα, στο
πρώτο παραδοτέο γίνονται τα εξής:
•Αντί για τον χαρακτήρα της Ruby χρησιμοποίησα έναν άλλο χαρακτήρα για
πρωταγωνιστή του παιχνιδιού, αυτό της μάγισσας.
Παρακάτω αναφέρονται οι αλλαγές που έχουν γίνει ακολουθώντας τα παραπάνω
δεδομένα:
•O χαρακτήρας της Ruby έχει αλλαχθεί με έναν νέο χαρακτήρα τον χαρακτήρα της
κότας ο οποίος είναι από την σελίδα https://9e0.itch.io/ . Παρακάτω φαίνεται ο νέος
χαρακτήρας https://9e0.itch.io/witches-pack (σκέφτομαι ίσως να προσθέσω εναν
ακομη για εναλλακτική επιλογή).
![image](https://user-images.githubusercontent.com/46855254/201205830-b8f1de8e-7886-445c-ad27-81d8e5045172.png)

•Επίσης, έδωσα στον χαρακτήρα κίνηση χρησιμοποιώντας το animation (όπως
είχαμε κάνει και στο μάθημα με χρήση script).
•Τέλος, δημιούργησα μια νέα πίστα με Tilemaps, η οποία διαμορφώθηκε με διάφορα
αντικείμενα και σκηνικά στον χώρο, απο την σελίδα https://petricakegames.itch.io/
όπου χρησιμοποίησα την πιστα https://petricakegames.itch.io/cosmic-lilac
![image](https://user-images.githubusercontent.com/46855254/201206018-3a9ec6c4-123c-4d30-8830-6a762a15bae4.png)
![image](https://user-images.githubusercontent.com/46855254/201206084-a920a763-48f2-410c-a07e-39f989170408.png)
![image](https://user-images.githubusercontent.com/46855254/201206174-f53b6acf-004c-4e2e-85bf-bd8c72a8fca3.png)
![image](https://user-images.githubusercontent.com/46855254/201206270-c200a2c3-cfa4-401c-9f59-53440d749a02.png)

Τελικό Αποτέλεσμα:
Τέλος δίνεται ένα τελικό screenshot του παιχνιδιού όπως είναι τώρα, με τις αλλαγές
που έχουν γίνει έως την φάση του πρώτου παραδοτέου.
![image](https://user-images.githubusercontent.com/46855254/201206417-bbecdc92-2b0b-4c01-b1e1-097e5ec7ccf2.png)

# 2nd Deliverable
Το δεύτερο παραδοτέο, αφορά την συνέχεια του σχεδιασμού της εφαρμογής. Ο σχεδιασμός ακολουθεί τις οδηγίες που έχουν δοθεί γραπτώς στο GitHub και από κάποια tutorials.
 
Αρχικά άλλαξα και επέκτεινα την πίστα, δημιουργώντας μια μεγαλύτερη με χρήση των ίδιων sprites με το πρώτο παραδοτέο. 
Τοποθέτησα Box-Collider 2D  στα μέρη που επιθυμούσα να μην πηγαίνει η μάγισσα, όπως για παράδειγμα τα όρια του παιχνιδιού, στη γέφυρα κ.α. Επίσης έκανα freeze rotation στον άξονα z στον χαρακτήρα ώστε να μην περιστρέφεται και να κινείται μόνο στους άξονες x και y.
![image](https://user-images.githubusercontent.com/46855254/208103901-803553cc-66b1-4553-af6c-bee3c56addcf.png)
 
Στη συνέχεια πρόσθεσα διάφορα αντικείμενα - Collectibles (φίλτρα) που θα δίνουν ζωή στον χαρακτήρα στον οποίο έδωσα μέγιστη ζωή 5.  
https://temok.itch.io/bottles-with-colorful-stuff
 ![image](https://user-images.githubusercontent.com/46855254/208103964-43e979ba-6cd5-41de-8256-47e56ee7e63f.png)
![image](https://user-images.githubusercontent.com/46855254/208103985-46ef748c-8e4f-4034-a306-1a9ddf07bd1a.png)

Δημιούργησα prefab καζάνια για damage zones, τους έδωσα components Rigidbody2D, Box-Collider 2D, και ενσωματωσα script ώστε εάν πάει ο χαρακτήρας του παιχνιδιού σ’ αυτά να χάνει μια ζωή. 
https://kaiowoka.itch.io/cauldron-cooking-pot-on-a-fire
 ![image](https://user-images.githubusercontent.com/46855254/208104077-a159d29d-a911-4c9d-b81e-1d81df3f9885.png)

Πρόσθεσα ως enemy την γάτα στην οποία έδωσα components Rigidbody2D, Box-Collider 2D, και ενσωματωσα script ώστε εάν πάει ο χαρακτήρας του παιχνιδιού σ’ αυτά να χάνει μια ζωή.
https://yukicrimson.itch.io/black-cat-sprite
 ![image](https://user-images.githubusercontent.com/46855254/208104133-71f01b5a-a6a1-4f50-b90f-8cc68e7442e5.png)

Σχετικά με το κομμάτι του animation, δημιούργησα φάκελο Animations στα assets μου όπου και πρόσθεσα τα animation κάθε στοιχείου. 
Για την μάγισσα διόρθωσα το καρέ στο photoshop, γιατι δεν φαινόταν αρκετά καλά τα πόδια, και έκανα τις εξής κινήσεις: δεξιά, αριστερά, πάνω και κάτω.
  ![image](https://user-images.githubusercontent.com/46855254/208104213-e6e8b3b5-d85f-430f-bc58-62528db02292.png)
![image](https://user-images.githubusercontent.com/46855254/208104237-8dedf1eb-a061-4dbf-a80d-ae73e80f8262.png)
![image](https://user-images.githubusercontent.com/46855254/208104256-91b71186-1077-44c1-a33a-e772538e7689.png)
![image](https://user-images.githubusercontent.com/46855254/208104277-59d6d1e7-caed-4a46-9fe2-6dcfb90aabc1.png)
 
Ακριβώς τις ίδιες κινήσεις έκανα και για τη γάτα (στη συνέχεια όμως την άφησα στάσιμη).
![image](https://user-images.githubusercontent.com/46855254/208104331-2550bd77-b284-4162-88e7-90cbe3adb8c2.png)

Επίσης έκανα animation για τα καζάνια, έτσι ώστε να φαίνονται πως βράζουν.
 
Για projectile επέλεξα να εκτοξεύει φωτιές ο enemy-γατα όταν την πλησιάζει ο χαρακτήρας. Ακολουθώντας τις οδηγίες.  
![image](https://user-images.githubusercontent.com/46855254/208104371-11a219bf-2350-4c54-83a2-060b95506863.png)

 
Τέλος, έκανα την κάμερα να ακολουθεί τον παίκτη όπως στις οδηγίες του tutorial camera - cinemachine.
 
Τελικό Αποτέλεσμα:
Τέλος δίνεται ένα τελικό screenshot του παιχνιδιού όπως είναι τώρα, με τις αλλαγές που έχουν γίνει έως την φάση του πρώτου παραδοτέου. 
![image](https://user-images.githubusercontent.com/46855254/208104397-81511edf-45c7-4faa-8bfd-69d5a49d9df7.png)


# 3rd Deliverable 


# Conclusions


# Sources
