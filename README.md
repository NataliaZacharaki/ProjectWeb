# ProjectWeb
Web application for a travel agency for Patras city.

Η εφαρμογή μας έχει ανέβει σε Web App του Azure.

Επισκεφτείτε το site μας ακολουθώντας τον σύνδεσμο: https://epatrasup1053586.azurewebsites.net/

Αν θέλετε ο εξυπηρετητής να τρέξει τοπικά ακολουθήστε τα παρακάτω βήματα.
Προκειμένου να είναι  δυνατή η πρόσβαση στην ιστοσελίδα απαιτούνται κάποια λογισμικά να είναι αποθηκευμένα στον υπολογιστή . 

Visual Studio Code προκειμένου να τρέχει ο εξυπηρετητής. https://code.visualstudio.com/download

Node.js https://nodejs.org/en/download/ 

Packages που χρησιμοποιήθηκαν στη Node.js .Στο τερματικό του Visual Studio Code πρέπει να κατέβουν τα εξής packages: 

1. express
2. express-handlebars
3. express-session
4. body-parser
5. bcrypt
6. multer
7. express-fileupload
8. mongodb
9. mongoose
10. handlebars

Το κατέβασμα ενός package γίνεται με την εντολή 'npm i name_package'

Για να αρχίσει ο εξυπηρετητής γράψτε στο terminal την εντολή: node app

Για να δείτε την ιστοσελίδα , ανοίξτε έναν browser και στο url πληκτρολογήστε  localhost:8080

Troubleshooting:

Σε περίπτωση που δεν τρέχει στο συγκεκριμένο  port που έχει οριστεί (8080), μεταβείτε στο αρχείο app.js στο vs code και αλλάξτε την τιμή του port στην γραμμή 2.

