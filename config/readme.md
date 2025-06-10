Questo README fornisce una panoramica completa dei campi standard disponibili nel tema Dawn. Per personalizzazioni avanzate, consulta la documentazione ufficiale di Shopify.

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

# Settings Data per Tema Dawn di Shopify

## Introduzione

Il file `settings_data.json` contiene tutte le configurazioni personalizzabili del tema Dawn di Shopify. Questo file si trova nella cartella `config/` del tema e definisce i valori predefiniti per tutte le impostazioni disponibili nel theme customizer.

## Struttura del File

```json
{
  "current": {
    // Impostazioni del tema attualmente attive
  },
  "presets": {
    // Preset predefiniti del tema
  }
}
```

## Campi Standard per il Tema Dawn

### **Colori**

```json
"colors_accent_1": "#121212",
"colors_accent_2": "#334fb4",
"colors_text": "#121212",
"colors_outline_button_labels": "#121212",
"colors_background_1": "#ffffff",
"colors_background_2": "#f3f3f3",
"colors_solid_button_labels": "#ffffff",
"gradient_accent_1": "",
"gradient_accent_2": "",
"gradient_background_1": "",
"gradient_background_2": ""
```

### **Typography**

```json
"type_header_font": "assistant_n4",
"heading_scale": 100,
"type_body_font": "assistant_n4",
"body_scale": 100
```

### **Layout e Spaziatura**

```json
"page_width": 1200,
"spacing_sections_desktop": 0,
"spacing_sections_mobile": 0
```

### **Pulsanti**

```json
"buttons_border_thickness": 1,
"buttons_border_opacity": 100,
"buttons_radius": 0,
"buttons_shadow_opacity": 0,
"buttons_shadow_horizontal_offset": 0,
"buttons_shadow_vertical_offset": 4,
"buttons_shadow_blur_radius": 5
```

### **Varianti Prodotto**

```json
"variant_pills_border_thickness": 1,
"variant_pills_border_opacity": 55,
"variant_pills_radius": 40,
"variant_pills_shadow_opacity": 0,
"variant_pills_shadow_horizontal_offset": 0,
"variant_pills_shadow_vertical_offset": 4,
"variant_pills_shadow_blur_radius": 5
```

### **Input e Form**

```json
"inputs_border_thickness": 1,
"inputs_border_opacity": 55,
"inputs_radius": 0,
"inputs_shadow_opacity": 0,
"inputs_shadow_horizontal_offset": 0,
"inputs_shadow_vertical_offset": 4,
"inputs_shadow_blur_radius": 5
```

### **Card Prodotto**

```json
"card_style": "standard",
"card_image_padding": 0,
"card_text_alignment": "left",
"card_color_scheme": "background-2",
"card_border_thickness": 0,
"card_border_opacity": 10,
"card_corner_radius": 0,
"card_shadow_opacity": 0,
"card_shadow_horizontal_offset": 0,
"card_shadow_vertical_offset": 4,
"card_shadow_blur_radius": 5
```

### **Badge**

```json
"badge_position": "bottom left",
"badge_corner_radius": 60
```

### **Media**

```json
"media_border_thickness": 1,
"media_border_opacity": 5,
"media_radius": 0,
"media_shadow_opacity": 0,
"media_shadow_horizontal_offset": 0,
"media_shadow_vertical_offset": 4,
"media_shadow_blur_radius": 5
```

### **Popup**

```json
"popup_border_thickness": 1,
"popup_border_opacity": 10,
"popup_corner_radius": 0,
"popup_shadow_opacity": 5,
"popup_shadow_horizontal_offset": 0,
"popup_shadow_vertical_offset": 4,
"popup_shadow_blur_radius": 5
```

### **Drawer**

```json
"drawer_border_thickness": 1,
"drawer_border_opacity": 10,
"drawer_shadow_opacity": 0,
"drawer_shadow_horizontal_offset": 0,
"drawer_shadow_vertical_offset": 4,
"drawer_shadow_blur_radius": 5
```

### **Social Media**

```json
"social_twitter_link": "",
"social_facebook_link": "",
"social_pinterest_link": "",
"social_instagram_link": "",
"social_tiktok_link": "",
"social_tumblr_link": "",
"social_snapchat_link": "",
"social_youtube_link": "",
"social_vimeo_link": ""
```

### **Favicon**

```json
"favicon": ""
```

### **Predictive Search**

```json
"predictive_search_enabled": true,
"predictive_search_show_vendor": false,
"predictive_search_show_price": true
```

### **Valuta**

```json
"currency_code_enabled": true
```

### **Sezioni**

Le sezioni sono definite in un oggetto `sections` separato:

```json
"sections": {
  "header": {
    "type": "header",
    "settings": {
      "color_scheme": "background-1",
      "logo_width": 90,
      "logo_position": "middle-left",
      "menu": "main-menu",
      "menu_type_desktop": "dropdown",
      "sticky_header_type": "on-scroll-up",
      "show_line_separator": true,
      "enable_country_selector": false,
      "enable_language_selector": false
    }
  },
  "footer": {
    "type": "footer",
    "settings": {
      "color_scheme": "background-1",
      "newsletter_enable": true,
      "newsletter_heading": "Subscribe to our emails",
      "enable_follow_on_shop": true,
      "show_social": false,
      "enable_country_selector": false,
      "enable_language_selector": false,
      "payment_enable": true,
      "show_policy": false,
      "margin_top": 48,
      "padding_top": 36,
      "padding_bottom": 36
    }
  }
}
```

## Note Importanti

1. **Backup**: Crea sempre un backup del file `settings_data.json` prima di apportare modifiche
2. **Validazione**: Assicurati che il JSON sia valido prima di salvare
3. **Presets**: I preset permettono di salvare diverse configurazioni del tema
4. **Sincronizzazione**: Le modifiche al file devono essere sincronizzate con il theme customizer

## Valori Comuni

### Color Schemes
- `background-1`: Schema colore principale
- `background-2`: Schema colore secondario  
- `inverse`: Schema colore invertito
- `accent-1`: Schema colore accent primario
- `accent-2`: Schema colore accent secondario

### Font Options
I font disponibili dipendono dalla configurazione del tema, esempi comuni:
- `assistant_n4`: Assistant Normal
- `source_sans_pro_n4`: Source Sans Pro Normal
- `montserrat_n4`: Montserrat Normal

### Card Styles
- `standard`: Stile standard
- `card`: Stile con bordo/sfondo
- `none`: Nessuno stile particolare


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


