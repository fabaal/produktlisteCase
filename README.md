# Produktliste - Case 

Dette projekt demonstrerer en simple moderne og minimalistisk produktliste-hjemmeside bygget med Umbraco og Tailwind CSS. Løsningen viser, hvordan man:

- Opsætte Umbraco-indholdstyper,
- Henter og viser produkter
- Bruger Tailwind til at lave et responsivt og stilrent design

Krav til løsningen 
1. Umbraco Opsætning
    • Opret en Produkt-dokumenttype med følgende felter:
        o Produktnavn (Tekst)
        o Beskrivelse (Rich Text)
        o Pris (Decimal)
        o Produktbillede (Media Picker)
    • Opret en Produktside-dokumenttype med:
        o Sidetitel (Tekst)
        o En visning af alle produkter (enten som child nodes eller hentet via query)

2. Frontend (Tailwind CSS)
    • På Produktsiden:
        o Vis produkterne i et responsivt grid (2–3 kolonner)
        o For hvert produkt skal følgende vises:
        ▪ Billede (gerne kvadratisk crop)
        ▪ Navn
        ▪ Kort beskrivelse (med tegnbegrænsning)
        ▪ Pris

    • Brug Tailwind CSS eller andet css framework til at style layoutet – sigt efter et moderne og rent
    udtryk.

3. Ekstra (Valgfrit)
    • Hover-effekter eller små animationer (f.eks. zoom ved hover)
    • Mobilvenligt layout
    • Brug et Partial View til at gengive produkt-elementet
    • Anvend Block List eller Block Grid Editor til layout (valgfrit)


Sådan kommer du igang 
 1. Clone projektet: 
    git clone https://github.com/fabaal/fabaal-UmbracoTailwindCase.git
   -  Naviger til projektmappen: 
        cd dit-projekt
   -  Kør projektet: 
        dotnet run

2. Umbraco backend login
    Gå til:http://localhost:5000/umbraco (eller porten du kører på)
        Log ind med:
        * Brugernavn: demo@demo.dk
        * Adgangskode: demo123456


Teknologier brugt
    - Umbraco CMS 
    - Tailwind CSS
    - ASP.NET Core
    - SQLite