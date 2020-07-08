
Naloge sem se lotil na sledeč način:
Sprva sem se lotil parsanja podatkov Evropskih držav iz REST API-ja. Uporabil sem knjižnico Retrofit. Pridobljene podatke sem shranil v vrednosti string,  te sem za začetek prikazoval v Logcat-u.
V nadaljevanju sem se lotil razvoja RecyclerViewa, ki vsebuje en ImageView in 3 TextViewe, za prikaz pridobljenih podatkov.
Ustvaril sem razred Model, v katerega sem shranjeval predhodno pridobljene vrednosti iz API-ja. Objekt razreda model, sem nato shranjeval v ArrayList imenovan List. V nadaljevanju sem uporabil sortedList, ki je služil sortiranju podatkov. V mojem primeru naraščajoče po prebivalcih. Ta sortedList, sem potem uporabil kot vhodne podatke za recyclerView.
Potrebno je bilo prikazati tudi zastavo države. Za to nalogo sem uporabil knjižnico GlideToVectorYou, ki je omogočala preprost prikaz slike iz pridobljenega URL naslova.
Sledila je implementacija iskalnika. Uporabil sem 3 editTexte za željen vnos iskanja in gumb, za proženje začetka poizvedbe. Iskalnik je implementiran s pomočjo pogoja if, v katerem se parsano ime, populacija in velikost države primerja z vnešenimi podatki iz editTextov. V primeru, da uporabnik pusti vnosna polja prazna in klikne gumb, se mu prikaže seznam vseh držav.
Po implementaciji iskalnika, sem se posvetil vizualnemu izgledu aplikacije. Definiral sem border.xml ter button.xml datoteki, ki sta bili namenjeni lepši predstavitvi podatkov. Aplikaciji sem nastavil tudi ozadje in definiral ikono.






