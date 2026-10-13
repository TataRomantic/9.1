#  Sekmīguma noteikšana

Šī ir vienkārša Python programma, kas palīdz skolēnam noskaidrot viņa sekmību mācību gada noslēgumā, balstoties uz ievadīto gada atzīmi.

##  Programmas nosacījumi un loģika
Programma pieprasa lietotājam ievadīt savu gada vērtējumu kā veselu skaitli (no 1 līdz 10) un veic šādu pārbaudi:
* **Ja vērtējums ir 4 vai augstāks:** tiek izvadīts paziņojums `"Esi veiksmīgi pabeidzis mācību gadu!"`
* **Citādi (ja vērtējums ir mazāks par 4):** tiek izvadīts paziņojums `"Vēl ir iespēju diena vai vasaras darbs!"`

##  Projekta struktūra
Projekts sastāv no šādiem failiem:
├── programmas_kods.py  <--  GALVENAIS FAILS (Palaidiet šo, lai darbinātu programmu)
└── README.md           <-- Šis apraksta un instrukciju fails

##  Lietošanas instrukcija
1. Pārliecinieties, ka jūsu datorā ir uzstādīts Python.
2. Atveriet un palaidiet failu `programmas_kods.py`.
3. Kad terminālī parādās aicinājums, ievadiet savu atzīmi (piemēram, `7`) un nospiediet **[Enter]**.
4. Ekrānā uzreiz parādīsies atbilstošais paziņojums par mācību gada noslēgumu.

##  Testēšanas apraksts
Programma ir pārbaudīta ar dažādiem ievades datiem (pozitīvo scenāriju, negatīvo scenāriju un robežvērtību), lai pārliecinātos, ka loģika strādā pareizi:

| Testa Nr. | Ievadītie dati (Vērtējums) | Sagaidāmais rezultāts ekrānā | Vai tests izdevās? |
| :---: | :---: | :--- | :---: |
| **1.** | `7` *(sekmīgs)* | "Esi veiksmīgi pabeidzis mācību gadu!" | ✅ Jā |
| **2.** | `3` *(nesekmīgs)* | "Vēl ir iespēju diena vai vasaras darbs!" | ✅ Jā |
| **3.** | `4` *(robežvērtība)* | "Esi veiksmīgi pabeidzis mācību gadu!" | ✅ Jā |
