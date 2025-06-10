📁 File Structure & Configuration
🔧 config/settings_data.json
COSA FA: Contiene le configurazioni globali del tema (colori, font, dimensioni)
QUANDO MODIFICARE:

✅ Per cambiare la palette colori dei 3 schemi
✅ Per modificare font e tipografia
✅ Per aggiustare dimensioni globali (bordi, ombre, angoli)
✅ Per impostazioni generali del tema

ESEMPI DI SETTINGS:
json{
  "colors_solid_button_background": "#2E5C8A",  // Colore pulsanti primari
  "buttons_border_thickness": "2",              // Spessore bordi pulsanti  
  "buttons_radius": "0",                        // Angoli squadrati (SEMPRE 0)
  "type_header_font": "montserrat_n6"          // Font titoli
}
🏠 templates/index.json
COSA FA: Definisce la struttura e contenuti della homepage
QUANDO MODIFICARE:

✅ Per cambiare l'ordine delle sezioni homepage
✅ Per modificare testi, titoli, descrizioni
✅ Per assegnare schemi colore alle sezioni
✅ Per configurare collezioni in evidenza

ESEMPI DI CONFIGURAZIONE:
json{
  "sections": {
    "image_banner": {
      "settings": {
        "heading": "Pompe e Ricambi per Motori Marini dal 1960",
        "text": "Qualità industriale, prezzi fino al 50% inferiori",
        "color_scheme": "background-1"  // Schema Maritime Professional
      }
    }
  }
}
🛍️ templates/product.json
COSA FA: Definisce la struttura e contenuti delle pagine prodotto
QUANDO MODIFICARE:

✅ Per modificare layout pagina prodotto
✅ Per aggiungere/rimuovere sezioni (FAQ, benefici, etc.)
✅ Per configurare le sezioni sotto il prodotto
✅ Per cambiare copy persuasivi

ESEMPI DI CONFIGURAZIONE:
json{
  "sections": {
    "collapsible_content": {
      "settings": {
        "heading": "Domande Frequenti",
        "color_scheme": "scheme-1"
      }
    }
  }
}
