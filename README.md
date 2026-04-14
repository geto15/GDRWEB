# GDRWEB
# Projecte Web - Fase 1: HTML (ASIKS)

Aquest projecte consisteix en el desenvolupament de l'estructura HTML per a una botiga de roba esportiva en línia anomenada **ASIKS**. La web està dissenyada amb una estètica moderna, centrada en l'experiència d'usuari i amb una estructura semàntica clara.

## 📂 1. Estructura de carpetes i arxius

L'organització del projecte (GDRWEB) segueix la següent jerarquia:

```text
GDRWEB/
│
├── css/                    # Fulls d'estil separats per components
│
├── imagenes/               # Imatges dels productes i categories
│
├── videos/                 # Recursos multimèdia (vídeos promocionals)
|
│__ audios/                 # Recursos d'àudio         
|
├── index.html              # Pàgina d'inici (Home)
├── contingut.html          # Distribuïdor principal del catàleg
├── ropa.html               # Categoria: Roba esportiva
├── zapatillas.html         # Categoria: Calçat
├── articulos.html          # Categoria: Accessoris i equipament
├── descuentos.html         # Pàgina de detall (Black Friday / Ofertes)
├── info.html               # Pàgina d'informació i contacte
└── README.md               # Documentació del projecte
├── sesion.html             # Pàgina de sessió d'usuari (login/signup)

A continuació es detalla la funció de cada arxiu HTML:

index.html: Pàgina principal. Inclou la capçalera amb navegació, un bàner principal, introducció a la marca i enllaços als fulls d'estil principals (estilo.css, menu.css, footer.css).

contingut.html: Pàgina central del catàleg. Funciona com un distribuïdor que mostra les categories principals per guiar l'usuari.

ropa.html, zapatillas.html, articulos.html: Pàgines de llistat de productes. Cadascuna conté una graella (Grid) amb els productes de la seva secció (imatge, títol, preu i enllaç).

black.html: Pàgina de detall especial dedicada a les ofertes de Black Friday o productes destacats amb descripcions ampliades.

info.html: Pàgina d'informació corporativa ("Nosaltres") que inclou dades de contacte i informació rellevant sobre el projecte/empresa.

sesion.html: Pàgina per a la gestió de l'inici de sessió i registre d'usuaris.


El treball s'ha dividit entre els tres membres del grup (GDR) de la següent manera:


Gerard
Estructura Base: Desenvolupament de l'index.html i la integració dels CSS  (menu.css, footer.css, estilo.css).

Pàgina de Detall: Creació de black.html (apartat Black Friday).

sesion.html: Desenvolupament de la pàgina de sessió d'usuari (login/signup).


David
Creació del distribuïdor(catàleg) contingut.html.

Desenvolupament de les subcategories: ropa.html, zapatillas.html i articulos.html.

integració dels CSS base que esta a tots els html  (estilos2.css). 

Implementació de la lògica de navegació entre productes.


Robert
Informació : Desenvolupament de l'apartat info.html (o secció d'informació).

Responsable de la integració de dades de l'empresa i formularis.

integració dels CSS (info.css) específics per a aquesta secció.


Formularis : Creació i estilització dels formularis de contacte i subscripció.
Es login estroba a en la part dreta superior de la pagina principal, y el formulari de contacte en la pàgina de contacte a la part inferior de la pàgina.

JAVASCRIPT:

Hem implementat 3 funcionalitats utilitzant javascript directament dins del arxiu index.html, sense necesitat d’arxius externs.


1. Mode clar / mode fosc

S’ha afegit un botó que permet canviar el fons de la pàgina entre mode clar (blanc) i mode fosc (negre).
Funcionament:

    El botó executa una funció JavaScript en fer clic.
    La funció detecta el color actual del fons del <body>.
    Si el fons és blanc, el canvia a negre i el text a blanc.
    Si el fons és fosc, torna al mode clar.

2. Efectes de ratolí
Hem implementat un efecte interactiu sobre un element de la pàgina (com un botó o un div).
Funcionament:

    En passar el ratolí per damunt l’element canvia de color i mida.
    En treure el ratolí l’element torna al seu estil original.

3. Mostrar / ocultar contingut
S’ha afegit un botó que permet mostrar o ocultar una secció de la pàgina.
Funcionament:

    El contingut està inicialment ocult (display: none).
    En fer clic al botó:
        -   Si el contingut està ocult, es mostra.
        -   Si està visible, s’oculta.


Validació formulari:

S'ha afegit validació en JavaScript a un formulari per comprovar que les dades siguin correctes abans d'enviar-les.

 Camps:

    Nom complet
    Telèfon
    Correu electrònic

Validacions:

    Nom: mínim 3 caràcters i no buit
    Telèfon: mínim 9 dígits
    Correu: ha de contenir "@" i "."

Funcionament

Quan es prem "Enviar", es validen els camps.
Si hi ha algun error, s'atura l'enviament i es mostra un missatge.

D'aquesta manera el formulari evita dades incorrectes i millora l'experiència de l'usuari.


