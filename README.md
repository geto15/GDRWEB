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
│
├── index.html              # Pàgina d'inici (Home)
├── contingut.html          # Distribuïdor principal del catàleg
├── ropa.html               # Categoria: Roba esportiva
├── zapatillas.html         # Categoria: Calçat
├── articulos.html          # Categoria: Accessoris i equipament
├── descuentos.html         # Pàgina de detall (Black Friday / Ofertes)
├── contacto.html           # Pàgina d'informació i contacte
└── README.md               # Documentació del projecte

A continuació es detalla la funció de cada arxiu HTML:

index.html: Pàgina principal. Inclou la capçalera amb navegació, un bàner principal, introducció a la marca i enllaços als fulls d'estil principals (estilo.css, menu.css, footer.css).

contingut.html: Pàgina central del catàleg. Funciona com un distribuïdor que mostra les categories principals per guiar l'usuari.

ropa.html, zapatillas.html, articulos.html: Pàgines de llistat de productes. Cadascuna conté una graella (Grid) amb els productes de la seva secció (imatge, títol, preu i enllaç).

descuentos.html: Pàgina de detall especial dedicada a les ofertes de Black Friday o productes destacats amb descripcions ampliades.

contacto.html: Pàgina d'informació corporativa ("Nosaltres") que inclou dades de contacte i informació rellevant sobre el projecte/empresa.

El treball s'ha dividit entre els tres membres del grup (GDR) de la següent manera:

Gerard
Estructura Base: Desenvolupament de l'index.html i la integració dels CSS base (menu.css, footer.css).

Pàgina de Detall: Creació de descuentos.html (apartat Black Friday).

David
Catàleg: Desenvolupament del nucli de productes.

Creació del distribuïdor contingut.html.

Desenvolupament de les subcategories: ropa.html, zapatillas.html i articulos.html.

Implementació de la lògica de navegació entre productes.

Robert
Informació i Contacte: Desenvolupament de l'apartat contacto.html (o secció d'informació).

Responsable de la integració de dades de l'empresa i formularis.