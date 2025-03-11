# Phonebook-GUI
1. The project aims to create a graphical user interface similar to a phonebook, where you can add, delete, or edit contacts. A GUI (Graphical User Interface) is a digital interface where a user interacts with graphical components such as icons, buttons, and menus.


2.	Tehnologii utilizate 

În realizarea proiectului am folosit ca limbaj de programare: Python - un limbaj flexibil, ușor de utilizat, care oferă programatorului numeroase frameworks și tools în mod gratuit. În cadrul acestuia, am folosit  biblioteca standard Tkinter ce este foarte usor de învățat pentru începători. Aceasta oferă facilități pentru construirea interfețelor grafice cu ferestre, butoane, etichete, casete de text si multe altele cu ajutorul cărora am dus la căpat cerința.

3.	Descrierea aplicației 
 	
- Interfața 
Pagina principala a interfeței, permite vizualizarea listei de contacte unde se pot accesa atât bara de căutare cât și butonoanele de adăugare de persoane, editare a contacului și stergere a acestuia.
![image](https://github.com/user-attachments/assets/ed99cd1c-7478-480b-8fe3-e7b2ec0c2b92)

În procesul de înregistrare, programul va cere utilizatorului să introducă numele și numărul de telefon specific proprietarului.  În procesul de logare programul va verifica daca sunt introduse ambele date de către utilizator,căci nu poate fi introdus un număr de telefon fără a specifica posesorul și nici invers, urmând să le introducă în baza de date și să le afișeze în lista de contacte.
![image](https://github.com/user-attachments/assets/de783b84-052f-46a6-9106-71392d315b6e)

	ArhitecturaSistem 
Importarea Bibliotecilor: 
![image](https://github.com/user-attachments/assets/22c198d0-c279-4632-b31d-b3f1efdb2bef)
  Aplicația PhoneBookApp este o agendă telefonică simplă realizată cu Tkinter, o bibliotecă de interfață grafică pentru Python. Utilizatorii pot adăuga, căuta, edita și șterge contacte.
Aplicația are următoarele funcționalități:

Acest cod implementează o simplă aplicație de gestionare a unei cărți de telefon, având următoarele fincționalități:
1.	Interfața grafică (GUI):
  •	Aplicația utilizează Tkinter pentru a crea o interfață grafică cu un frame principal.
  •	Există trei cadre distincte pentru introducerea contactelor, căutarea acestora și afișarea într-un Treeview (o listă de arbore) pentru a vizualiza și interacționa cu contactele.
2.	Adăugarea, Editarea și Ștergerea Contactelor:
  •	Utilizatorul poate introduce un nume și un număr de telefon în câmpurile corespunzătoare și apăsa butonul "Add Contact" pentru a adăuga un nou contact.
  •	Contactele sunt afișate în Treeview, unde utilizatorul poate selecta un contact.
  •	Există butoane pentru editarea și ștergerea contactelor selectate.
3.	Căutarea și Filtrarea Contactelor:
  •	Există un câmp de căutare unde utilizatorul poate introduce un termen de căutare și lista de contacte va fi filtrată în funcție de acest termen.
4.	Sortarea Contactelor:
  •	Există o metodă sort_contacts care sortează contactele în funcție de nume, iar aceasta poate fi apelată prin intermediul unui buton sau altă acțiune din interfața grafică.
5.	Salvarea și Încărcarea Contactelor din Fișier:
  •	Contactele sunt salvate într-un fișier numit "contacts.txt" și pot fi încărcate la pornirea aplicației.
  •	Fișierul conține perechi de nume și numere de telefon separate prin două puncte (:).
6.	Feedback și Stare:
  •	Există o etichetă în partea de jos a ferestrei care furnizează feedback utilizatorului cu privire la starea curentă a aplicației (de exemplu, "Contact added", "Contact deleted", "Contacts loaded", etc.).
7.	Stilizare:
  •	Utilizează ttk.Style pentru a aplica un aspect stilizat butoanelor și Treeview.
8.	Modularitate:
  •	Codul este structurat într-o clasă PhoneBookApp, ceea ce îl face ușor de înțeles și de extins.
9.	Main Loop:
  •	Programul principal începe și rulează bucla principală a aplicației utilizând root.mainloop().

Concluzii:
Această aplicație permite utilizatorului să adauge, să editeze, să șteargă și să caute contacte, și să le salveze într-un fișier. Este un exemplu simplu de o aplicație de gestionare a contactelor cu interfață grafică.




