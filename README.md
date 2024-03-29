# O projektu

Tutoriálový projekt z kurzu [Next.js & React - The Complete Guide](https://www.udemy.com/course/nextjs-react-the-complete-guide/)

Autor: Maximilian Schwarzmüller

---

### Co jsem se naučil

Oproti klasickému Reactu jsem si s Next.js vyzkoušel řadu užitečných fičur, jako jsou:

- file-based routing
- client side prerendering s **getStaticProps**
- server side prerendering s **getServerSideProps**
- lazy loading obrázků s **Image**
- nastavování backendu s **API Routes**

### Funkce

Vytvořeno pomocí **create-next-app**.

K lokálnímu stylování komponentů pouužity **CSS Modules**.

Aplikace pomocí **Fetch API** stáhne seznam eventů z [Firebase](https://firebase.google.com/) a dynamicky je zobrazí uživateli.

Možnost pod eventy přidávat komentáře, a přihlásit se k odběru newsletteru, data se ukládají do **MongoDB** Atlas databáze.

State management řešen pomocí **useState** & **useContext**.

Pozn. MongoDB cluster vyžaduje k připojení předem schválenou IP adresu, zmáčknutí tlačítka "show comments" a "register" (k newsletteru) vyvolají error.

[**DEMO**](https://next-events-app.vercel.app/)
