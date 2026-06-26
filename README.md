# Moderní webová prezentace – Cheeseburger

## 1. Popis projektu

Interaktivní jednostránková webová aplikace, která slouží jako prezentace cheeseburgeru. Web obsahuje zajímavá fakta o cheeseburgeru a automatický počítač kalorií, který dynamicky reaguje na každou přidanou vrstvu burgeru. Uživatel si může sestavit vlastní burger a okamžitě vidí změnu kalorické hodnoty.

---

## 2. Použité technologie

* **HTML5 & CSS3** (struktura a stylování)
* **JavaScript** (interaktivita, manipulace s DOM, výpočet kalorií)
* **IDE:** Visual Studio Code
* **Nástroje a zdroje:** W3Schools (vzdělávací materiály), Gemini a GitHub Copilot (AI asistenti)

---

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
│   ├── upper_bun.png
│   ├── ss1.png
│   └── ss2.png
│
├── cheeseburger.html
├── sitemap.xml
├── robots.txt
└── README.md
```

---

## 4. Technický rozbor

### a) Sloučení kódu do jednoho souboru pro one-page web

#### Teoretický popis řešení

Sloučení HTML, CSS a JavaScriptu do jednoho souboru je u malé jednostránkové aplikace výhodné. Project je jednodušší na správu.

#### Ukázka kódu

```html
<body>
    <style>
        body {
            background-color: #f5bb78;
        }
    </style>

    <script>
        function goDown() {
        }
    </script>
</body>
```

### b) Využití datových atributů pro výpočet kalorií

#### Teoretický popis řešení

Kalorické hodnoty jednotlivých ingrediencí jsou ukládány pomocí HTML atributů `data-kcal`. JavaScript následně tyto hodnoty načítá přes DOM a automaticky přepočítává výsledný počet kalorií.

#### Ukázka kódu

```html
<img src="Images/bottom_bun.png"
     class="bottom-bun toping"
     data-kcal="150"
     alt="Bottom bun">

<img src="Images/mustard.png"
     class="mustard toping hidden"
     data-kcal="10"
     alt="Mustard">
```

### c) SEO (Search Engine Optimization)

#### Teoretický popis řešení

Projekt využívá základní SEO principy. HTML dokument obsahuje správně definovaný název stránky, jazyk dokumentu a meta viewport. Součástí projektu jsou také soubory `sitemap.xml` a `robots.txt`, které pomáhají vyhledávačům při indexaci webu.

#### Ukázka kódu

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Cheeseburger</title>
```

### d) Přístupnost (Accessibility)

#### Teoretický popis řešení

Web používá alternativní texty (`alt`) u obrázků, což umožňuje lepší přístupnost pro uživatele čteček obrazovky. Rozhraní je navrženo tak, aby bylo jednoduché a přehledné.

#### Ukázka kódu

```html
<img src="Images/cheeze.png"
     class="cheeze toping hidden"
     data-kcal="80"
     alt="Cheese slice">
```

### e) UX/UI Design

#### Teoretický popis řešení

Uživatelské rozhraní bylo navrženo s důrazem na jednoduchost a intuitivnost. Uživatel okamžitě vidí výsledek svých akcí, protože se burger skládá v reálném čase a současně se aktualizuje počet kalorií.

#### Hlavní principy

* jednoduché ovládání.
* okamžitá vizuální zpětná vazba.
* snadná orientace uživatele.

### f) Optimalizace výkonu

#### Teoretický popis řešení

Projekt využívá pouze lokální obrázky a čistý JavaScript bez externích knihoven. Díky tomu se stránka načítá rychle a vytváří minimum HTTP požadavků.

#### Ukázka kódu

```javascript
document.addEventListener("DOMContentLoaded", () => {
});
```

---

## 5. AI Deník

Při vývoji projektu byly využity nástroje Gemini a GitHub Copilot. AI pomáhala především při hledání chyb v syntaxi, návrhu funkcí a vysvětlování některých webových technologií.

Počítání kalorií a většina zajímavých faktů o cheeseburgerech byly vytvořeny s pomocí AI a následně upraveny pro potřeby projektu.

### Příklady použitých promptů

* Jak zobrazit počet kalorií nad přidanou ingrediencí v burgeru?
* Jak vytvořit sitemap.xml pro one-page web?
* Co je meta tag v HTML?
* Jak správně používat data atributy v JavaScriptu?
* Jak spravně udělat README

(Většina promptů byla původně zadávána v angličtině.)

---

## 6. Instalace a spuštění

1. Stáhněte si celou složku projektu Burger.
2. Otevřete složku ve Visual Studio Code.
3. Nainstalujte rozšíření Live Server.
4. Klikněte pravým tlačítkem myši na soubor `cheeseburger.html`.
5. Zvolte možnost **Open with Live Server**.

Alternativně lze projekt spustit i otevřením souboru `cheeseburger.html` přímo v internetovém prohlížeči.

---

## 7. Galerie screenshotů

![Screenshot 1](Images/ss1.png)

![Screenshot 2](Images/ss2.png)

![Screenshot 3](Images/ss3.jpg)
