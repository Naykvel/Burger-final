## 1. Interaktivní jednostránková webová aplikace, která slouží jako prezentace cheeseburgeru.
Web obsahuje zajímavá fakta a automatický počítač kalorií, který dynamicky reaguje na každou přidanou vrstvu burgeru.



## 2. Použité technologie
- **HTML5 & CSS3** (struktura a stylování)
- **JavaScript (ES6+)** (interaktivita, manipulace s DOM, výpočet kalorií)
- **IDE:** Visual Studio Code
- **Nástroje a zdroje:** W3Schools (vzdělávací materiály), Gemini & GitHub Copilot (AI asistenti)

## 3. Adresářová struktura
```text
Burger/
│
├── Images/
│   ├── arrow.png
│   ├── bottom_bun.png
│   ├── cheeze.png
│   ├── ketchup.png
│   ├── latuce.png
│   ├── mustard.png
│   ├── onions.png
│   ├── pattie.png
│   ├── pickles.png
│   ├── shadow.png
│   ├── tomatoes.png
│   └── upper_bun.png
│
├── cheseburger.html
└── README.md

## 4. Technický rozbor:
a. Sloučení kódu do jednoho souboru pro one-page web:
    Teoretický popis řešení: Sloučení kódu do jednoho souboru namísto rozdělování projektu do několika externích souborů je u malé jednostránkové aplikace výhodnější. Celý projekt se drží pohromadě, rychleji se načítá a zjednodušuje to správu kódu.
Výstřižek kódu:
<body>
    //<style> body { background-color: #f5bb78; } </style>
    //<script> function goDown() { ... } </script>
</body>

b.Využití datových atributů pro výpočet kalorií
    Teorirycky popis řešení: Pro ukládání hodnot přímo do HTML elementů se používal vestavěné data atributy přes DOM
Výstřižek kódu: 
//<img src="bottom_bun.png" class="bottom-bun toping" data-kcal="150" alt="burger">
//<img src="mustard.png" class="mustard toping hidden" data-kcal="10" alt="burger">

## 5. AI Deník: 
AI mnohem pomahal s funkcemi a opravou špatné syntaxe, ale počitatel kalorii a fakty o cheseburgerach skoro uplně vygenerovane.
    zajimavé promty: Jak by ty doporučil a udelal bych, aby když přidavá se ingredient do burgeru, tak nad něj bych psal počet kilokalorii 
    
    (Však originalně psál jsem v anglištině pronty)

6. Instalace a spuštění:
    Stáhněte si celou složku Burger, která obsahuje soubor cheseburger.html a podsložku Images. Otevřete složku Burger ve Visual Studio Code, musite m9t nainstalované rozšíření Live Server, klikněte pravým tlačítkem myši na soubor cheseburger.html a zvolte "Open with Live Server" (Alternativní spuštění: Projekt lze spustit i obyčejným dvojitým kliknutím na soubor cheseburger.html přímo ve správci souborů)

7. ![screebshot](Images/ss1.png)
![screenshot](Images/ss2.png)



//I přes to že zadani ja asi ne splníl, mi libilo dělat to zadani

//přepisoval jsem to 3 krat kvuli chybam a "ne perfektní" vyhledu. ;_; však, už je deadline

//to je one page web, jak musím udělat sitemap T_T