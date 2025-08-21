# Výstava obrazů A.Muchy - Fiktivní Webová Stránka

## 📋 Popis projektu

Tento projekt představuje **fiktivní webovou stránku** pro výstavu obrazů Alfonse Muchy ve Výstavišti Ostrava. Jedná se o celodenní cvičení z HTML, CSS a Bootstrapu vytvořené během školní výuky.

## 👨‍💻 Autor
**Robin Lassak**

## 🎯 Cíle projektu
- Praktické procvičení HTML5
- Stylování pomocí CSS3 a SCSS
- Implementace Bootstrap 5 frameworku
- Vytvoření responzivního designu
- Práce s formuláři a modálními okny

## 🛠️ Použité technologie

### Frontend
- **HTML5** - Struktura webové stránky
- **CSS3** - Stylování a layout
- **SCSS/Sass** - Preprocessor pro CSS
- **Bootstrap 5.3.3** - CSS framework pro responzivní design
- **Bootstrap Icons** - Ikony pro sociální sítě

### Nástroje
- **Node.js** - Package management
- **Sass** - Kompilace SCSS do CSS

## 📁 Struktura projektu

```
FictionalWeb/
├── index.html              # Hlavní HTML soubor
├── package.json            # Node.js dependencies
├── package-lock.json       # Lock file pro dependencies
├── README.md              # Tento soubor
├── scss/
│   ├── custome.scss       # SCSS zdrojový soubor
│   ├── custome.css        # Zkompilovaný CSS
│   └── custome.css.map    # Source map pro debugging
├── Grafika/               # Obrázky a grafické prvky
│   ├── Pozadi.jpg         # Hlavní pozadí
│   ├── Pozadi2.jpg        # Sekundární pozadí
│   ├── pexels-gabby-k-5302905.jpg  # Hero sekce pozadí
│   ├── Technika.jpg       # Obrázek pro sekci Technika
│   ├── Umeni.jpg          # Obrázek pro sekci Umění
│   └── Priroda.jpg        # Obrázek pro sekci Příroda
└── node_modules/          # Node.js dependencies
```

## 🎨 Funkce webové stránky

### 1. **Navigace**
- Fixní navigační lišta s Bootstrap komponenty
- Responzivní hamburger menu pro mobilní zařízení
- Smooth scroll na jednotlivé sekce

### 2. **Hero sekce (Home)**
- Fullscreen pozadí s overlay efektem
- Hlavní nadpis "Výstava obrazů A.Muchy"
- Tlačítka pro rezervaci vstupenek a odkaz na Wikipedii
- Responzivní design

### 3. **Rezervační formulář (Modal)**
- Bootstrap modal s formulářem pro rezervaci
- Validace formulářových polí
- Pola: Jméno, Email, Telefon, Počet vstupenek, Datum

### 4. **Sekce "O nás"**
- Tři sloupce s různými tématy (Technika, Umění, Příroda)
- Obrázky s responzivním designem
- Použití různých Google Fonts (Roboto, Lato, Work Sans)

### 5. **Galerie**
- Grid layout s obrázky
- Lightbox efekt pro zobrazení obrázků

### 6. **Ohlasy**
- Kontaktní formulář
- Validace vstupních polí

### 7. **Kontakty**
- Kontaktní informace společnosti
- Sociální sítě s Bootstrap ikonami
- Google Maps iframe

## 🚀 Instalace a spuštění

### Předpoklady
- Node.js (verze 14 nebo vyšší)
- npm (Node Package Manager)

### Kroky instalace

1. **Naklonování projektu**
   ```bash
   git clone [URL repozitáře]
   cd FictionalWeb
   ```

2. **Instalace dependencies**
   ```bash
   npm install
   ```

3. **Kompilace SCSS (pokud je potřeba)**
   ```bash
   npx sass scss/custome.scss scss/custome.css
   ```

4. **Spuštění**
   - Otevřete `index.html` v prohlížeči
   - Nebo použijte lokální server:
   ```bash
   npx http-server
   ```

## 📱 Responzivní design

Webová stránka je plně responzivní a optimalizovaná pro:
- **Desktop** (1200px+)
- **Tablet** (768px - 1199px)
- **Mobile** (do 767px)

## 🎨 Design prvky

### Barevné schéma
- Primární: Bootstrap secondary (šedá)
- Text: Černá na bílém pozadí
- Overlay: Poloprůhledná černá (rgba(0, 0, 0, 0.5))

### Typografie
- **Google Fonts**: Roboto, Lato, Work Sans
- **Bootstrap typography classes**: display-1, text-uppercase, atd.

### Komponenty
- Bootstrap Navbar
- Bootstrap Modal
- Bootstrap Forms
- Bootstrap Grid System
- Bootstrap Icons

## 📝 Poznámky k vývoji

- Projekt je vytvořen jako **cvičení** pro školní účely
- Jedná se o **fiktivní** výstavu - všechny informace jsou smyšlené
- Kód je strukturovaný pro snadné pochopení a údržbu
- Používá moderní webové standardy a best practices

## 🔗 Externí odkazy

- **Bootstrap 5.3.3**: https://getbootstrap.com/
- **Bootstrap Icons**: https://icons.getbootstrap.com/
- **Google Fonts**: https://fonts.google.com/
- **Alfons Mucha (Wikipedia)**: https://cs.wikipedia.org/wiki/Alfons_Mucha

## 📄 Licence

Tento projekt je vytvořen pro vzdělávací účely. Všechna práva vyhrazena autorovi.

---

*Vytvořeno jako školní projekt pro procvičení HTML, CSS a Bootstrapu*
