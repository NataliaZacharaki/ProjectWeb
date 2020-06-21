# ProjectWeb
Web application for a travel agency for Patras city.

Αν θέλετε ο εξυπηρετητής να τρέχει τοπικά ακολουθήστε τα παρακάτω βήματα.
Προκειμένου να είναι  δυνατή η πρόσβαση στην ιστοσελίδα απαιτούνται κάποια λογισμικά να είναι αποθηκευμένα στον υπολογιστή μας . 

Visual Studio Code προκειμένου να τρέχει ο εξυπηρετητής. https://code.visualstudio.com/download

Node.js https://nodejs.org/en/download/

Packages που χρησιμοποιήθηκαν στη Node.js .Στο τερματικό του Visual Studio Code πρέπει να κατέβουν τα εξής packages: 

express,

express-handlebars,

express-session,

body-parser,

bcrypt,

multer,

express-fileupload,

mongodb,

mongoose,

handlebars,

Το κατέβασμα ενός package γίνεται με την εντολή npm i name_package

Για να αρχίσει ο εξυπηρετητής γράψτε στο terminal την εντολή: node server.js

Για να δείτε την ιστοσελίδα , ανοίξτε έναν browser και στο url πληκτρολογήστε  localhost:8080

Troubleshooting:

Σε περίπτωση που δεν τρέχει στο συγκεκριμένο  port που έχει οριστεί (8080), μεταβείτε στο αρχείο server.js στο vs code και αλλάξτε την τιμή του port στην γραμμή 2.

