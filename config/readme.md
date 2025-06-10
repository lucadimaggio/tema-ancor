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


# Guida Completa - index.json per Tema Dawn

## 🏠 Introduzione

Il file `templates/index.json` definisce la struttura e i contenuti della homepage del tuo store Shopify. È il template più importante perché determina la prima impressione dei visitatori.

**POSIZIONE:** `templates/index.json`

## 🎯 Quando Modificare index.json

- ✅ Per cambiare l'ordine delle sezioni homepage
- ✅ Per modificare testi, titoli, descrizioni
- ✅ Per assegnare schemi colore alle sezioni
- ✅ Per configurare collezioni in evidenza
- ✅ Per aggiungere/rimuovere sezioni
- ✅ Per personalizzare call-to-action
- ✅ Per configurare banner promozionali

## 📋 Struttura Base

```json
{
  "sections": {
    "section_id": {
      "type": "section_type",
      "blocks": {
        "block_id": {
          "type": "block_type",
          "settings": {
            // Impostazioni del blocco
          }
        }
      },
      "block_order": ["block_id"],
      "settings": {
        // Impostazioni della sezione
      }
    }
  },
  "order": ["section_id"]
}
```

## 🔧 Sezioni Principali Disponibili

### **1. Image Banner (Hero Section)**

```json
"image_banner": {
  "type": "image-banner",
  "settings": {
    "image": "shopify://shop_images/hero-banner.jpg",
    "image_overlay_opacity": 0,
    "image_height": "large",
    "desktop_content_position": "middle-center",
    "show_text_box": false,
    "desktop_content_alignment": "center",
    "color_scheme": "background-1",
    "image_behavior": "none",
    "mobile_content_alignment": "center",
    "stack_images_on_mobile": false,
    "show_text_below": false,
    "heading": "Il Tuo Titolo Principale",
    "heading_size": "h0",
    "text": "Sottotitolo descrittivo che cattura l'attenzione",
    "button_label": "Scopri di più",
    "button_link": "/collections/all",
    "button_style_secondary": false
  }
}
```

**Opzioni Chiave:**
- `image_height`: "small", "medium", "large", "adapt"
- `desktop_content_position`: "top-left", "top-center", "top-right", "middle-left", "middle-center", "middle-right", "bottom-left", "bottom-center", "bottom-right"
- `heading_size`: "h2", "h1", "h0"

### **2. Rich Text**

```json
"rich_text": {
  "type": "rich-text",
  "blocks": {
    "heading": {
      "type": "heading",
      "settings": {
        "heading": "Benvenuto nel nostro store",
        "heading_size": "h1"
      }
    },
    "text": {
      "type": "text",
      "settings": {
        "text": "<p>Descrizione dettagliata della tua azienda e dei tuoi valori.</p>"
      }
    },
    "button": {
      "type": "button",
      "settings": {
        "button_label": "Esplora i prodotti",
        "button_link": "/collections/all",
        "button_style_secondary": false,
        "button_label_2": "",
        "button_link_2": "",
        "button_style_secondary_2": false
      }
    }
  },
  "block_order": ["heading", "text", "button"],
  "settings": {
    "desktop_content_position": "center",
    "content_alignment": "center",
    "color_scheme": "background-1",
    "full_width": true,
    "padding_top": 40,
    "padding_bottom": 52
  }
}
```

### **3. Featured Collection**

```json
"featured_collection": {
  "type": "featured-collection",
  "settings": {
    "title": "Prodotti in Evidenza",
    "heading_size": "h2",
    "description": "",
    "show_description": false,
    "description_style": "body",
    "collection": "featured-products",
    "products_to_show": 8,
    "columns_desktop": 4,
    "full_width": false,
    "show_view_all": true,
    "view_all_style": "solid",
    "enable_desktop_slider": false,
    "color_scheme": "background-1",
    "image_ratio": "adapt",
    "image_shape": "default",
    "show_secondary_image": false,
    "show_vendor": false,
    "show_rating": false,
    "enable_quick_add": false,
    "columns_mobile": "2",
    "swipe_on_mobile": false,
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

**Opzioni Chiave:**
- `products_to_show`: 4, 8, 12, 16, 20
- `columns_desktop`: 2, 3, 4, 5
- `columns_mobile`: "1", "2"
- `image_ratio`: "adapt", "portrait", "square"

### **4. Collage**

```json
"collage": {
  "type": "collage",
  "blocks": {
    "collection": {
      "type": "collection",
      "settings": {
        "collection": "your-collection"
      }
    },
    "product": {
      "type": "product",
      "settings": {
        "product": "your-product",
        "second_image": false
      }
    },
    "video": {
      "type": "video",
      "settings": {
        "video_url": "https://www.youtube.com/watch?v=_9VUPq3SxOc",
        "description": "Descrizione del video",
        "image_padding": false
      }
    }
  },
  "block_order": ["collection", "product", "video"],
  "settings": {
    "heading": "Multimedia",
    "heading_size": "h2",
    "desktop_layout": "left",
    "mobile_layout": "collage",
    "card_styles": "product-card-wrapper",
    "color_scheme": "background-1",
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **5. Video**

```json
"video": {
  "type": "video",
  "settings": {
    "heading": "",
    "heading_size": "h1",
    "enable_video_looping": false,
    "video_url": "https://www.youtube.com/watch?v=_9VUPq3SxOc",
    "description": "",
    "full_width": false,
    "color_scheme": "background-1",
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **6. Multirow**

```json
"multirow": {
  "type": "multirow",
  "blocks": {
    "row1": {
      "type": "row",
      "settings": {
        "image": "shopify://shop_images/feature1.jpg",
        "caption": "",
        "heading": "Qualità Superiore",
        "text": "<p>Descrizione della caratteristica principale.</p>",
        "button_label": "",
        "button_link": ""
      }
    },
    "row2": {
      "type": "row",
      "settings": {
        "image": "shopify://shop_images/feature2.jpg",
        "caption": "",
        "heading": "Spedizione Veloce",
        "text": "<p>Consegna rapida in tutta Italia.</p>",
        "button_label": "",
        "button_link": ""
      }
    }
  },
  "block_order": ["row1", "row2"],
  "settings": {
    "image_height": "medium",
    "desktop_image_width": "medium",
    "heading_size": "h1",
    "text_style": "body",
    "button_style": "secondary",
    "swipe_on_mobile": false,
    "color_scheme": "background-1",
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **7. Collection List**

```json
"collection_list": {
  "type": "collection-list",
  "blocks": {
    "collection1": {
      "type": "featured_collection",
      "settings": {
        "collection": "motors"
      }
    },
    "collection2": {
      "type": "featured_collection",
      "settings": {
        "collection": "pumps"
      }
    }
  },
  "block_order": ["collection1", "collection2"],
  "settings": {
    "title": "Le Nostre Categorie",
    "heading_size": "h2",
    "image_ratio": "square",
    "columns_desktop": 3,
    "color_scheme": "background-1",
    "show_view_all": false,
    "columns_mobile": "1",
    "swipe_on_mobile": false,
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **8. Newsletter**

```json
"newsletter": {
  "type": "newsletter",
  "settings": {
    "color_scheme": "background-1",
    "full_width": true,
    "padding_top": 40,
    "padding_bottom": 52
  }
}
```

## 🎨 Color Schemes Disponibili

- `background-1`: Schema principale
- `background-2`: Schema secondario
- `inverse`: Schema invertito
- `accent-1`: Schema accent primario
- `accent-2`: Schema accent secondario

## 📱 Impostazioni Responsive

### Desktop
- `columns_desktop`: 2, 3, 4, 5
- `desktop_content_position`: posizionamento contenuto
- `desktop_image_width`: "small", "medium", "large"

### Mobile
- `columns_mobile`: "1", "2"
- `swipe_on_mobile`: true/false
- `mobile_content_alignment`: "left", "center", "right"

## ⚙️ Impostazioni Comuni

### Padding e Spaziatura
```json
"padding_top": 36,      // Spaziatura superiore (0-100)
"padding_bottom": 36    // Spaziatura inferiore (0-100)
```

### Dimensioni Heading
- `h0`: Extra Large
- `h1`: Large
- `h2`: Medium
- `hsmall`: Small

### Stili Button
- `button_style_secondary`: false (primario) / true (secondario)
- `view_all_style`: "solid", "outline", "link"

## 🚀 Esempio Homepage Completa

```json
{
  "sections": {
    "image_banner": {
      "type": "image-banner",
      "settings": {
        "heading": "Pompe e Ricambi Marini dal 1960",
        "text": "Qualità industriale, prezzi competitivi",
        "button_label": "Scopri i prodotti",
        "button_link": "/collections/all",
        "color_scheme": "background-1"
      }
    },
    "featured_collection": {
      "type": "featured-collection",
      "settings": {
        "title": "Prodotti più venduti",
        "collection": "bestsellers",
        "products_to_show": 8,
        "columns_desktop": 4
      }
    },
    "multirow": {
      "type": "multirow",
      "blocks": {
        "quality": {
          "type": "row",
          "settings": {
            "heading": "Qualità Certificata",
            "text": "<p>Prodotti testati e garantiti</p>"
          }
        }
      },
      "block_order": ["quality"]
    },
    "newsletter": {
      "type": "newsletter"
    }
  },
  "order": [
    "image_banner",
    "featured_collection", 
    "multirow",
    "newsletter"
  ]
}
```

## 💡 Best Practices

1. **Ordine Logico**: Posiziona le sezioni in ordine di importanza
2. **Performance**: Non usare troppe sezioni che caricano molte immagini
3. **Mobile First**: Testa sempre su dispositivi mobili
4. **Call-to-Action**: Includi CTA chiari e visibili
5. **Coerenza**: Mantieni uno schema colori coerente
6. **Testing**: Testa sempre le modifiche prima di pubblicare

## ⚠️ Note Importanti

- **Backup**: Fai sempre un backup prima delle modifiche
- **Validazione JSON**: Verifica che il JSON sia valido
- **Performance**: Troppi prodotti possono rallentare il caricamento
- **SEO**: Usa heading appropriati per la SEO
- **Accessibilità**: Assicurati che i contrasti siano sufficienti

  
🛍️ templates/product.json
COSA FA: Definisce la struttura e contenuti delle pagine prodotto
QUANDO MODIFICARE:

✅ Per modificare layout pagina prodotto
✅ Per aggiungere/rimuovere sezioni (FAQ, benefici, etc.)
✅ Per configurare le sezioni sotto il prodotto
✅ Per cambiare copy persuasivi

# Guida Completa - product.json per Tema Dawn

## 🛍️ Introduzione

Il file `templates/product.json` definisce la struttura e i contenuti delle pagine prodotto del tuo store Shopify. È fondamentale per le conversioni e l'esperienza utente durante l'acquisto.

**POSIZIONE:** `templates/product.json`

## 🎯 Quando Modificare product.json

- ✅ Per modificare layout pagina prodotto
- ✅ Per aggiungere/rimuovere sezioni (FAQ, benefici, etc.)
- ✅ Per configurare le sezioni sotto il prodotto
- ✅ Per cambiare copy persuasivi
- ✅ Per personalizzare form di acquisto
- ✅ Per aggiungere contenuti di trust building
- ✅ Per configurare prodotti correlati
- ✅ Per ottimizzare per conversioni

## 📋 Struttura Base

```json
{
  "sections": {
    "main": {
      "type": "main-product",
      "blocks": {
        // Blocchi del prodotto principale
      },
      "block_order": ["block_id"],
      "settings": {
        // Impostazioni della sezione principale
      }
    },
    "section_id": {
      "type": "section_type",
      "settings": {
        // Impostazioni sezioni aggiuntive
      }
    }
  },
  "order": ["main", "section_id"]
}
```

## 🔧 Sezione Main Product

### **Configurazione Base**

```json
"main": {
  "type": "main-product",
  "blocks": {
    "vendor": {
      "type": "text",
      "settings": {
        "text": "{{ product.vendor }}",
        "text_style": "uppercase"
      }
    },
    "title": {
      "type": "title",
      "settings": {}
    },
    "price": {
      "type": "price",
      "settings": {}
    },
    "variant_picker": {
      "type": "variant_picker",
      "settings": {
        "picker_type": "button"
      }
    },
    "quantity_selector": {
      "type": "quantity_selector",
      "settings": {}
    },
    "buy_buttons": {
      "type": "buy_buttons",
      "settings": {
        "show_dynamic_checkout": true,
        "show_gift_card_recipient": false
      }
    },
    "description": {
      "type": "description",
      "settings": {}
    },
    "share": {
      "type": "share",
      "settings": {
        "share_label": "Condividi"
      }
    }
  },
  "block_order": [
    "vendor",
    "title", 
    "price",
    "variant_picker",
    "quantity_selector",
    "buy_buttons",
    "description",
    "share"
  ],
  "settings": {
    "enable_sticky_info": true,
    "color_scheme": "scheme-1",
    "media_size": "large",
    "constrain_to_viewport": true,
    "media_fit": "contain",
    "gallery_layout": "stacked",
    "media_position": "left",
    "image_zoom": "lightbox",
    "mobile_thumbnails": "hide",
    "hide_variants": true,
    "enable_video_looping": false,
    "padding_top": 36,
    "padding_bottom": 12
  }
}
```

### **Blocchi Disponibili per Main Product**

#### **1. Text Block**
```json
"custom_text": {
  "type": "text",
  "settings": {
    "text": "Testo personalizzato o liquid",
    "text_style": "body"
  }
}
```

**Opzioni text_style:**
- `body`: Testo normale
- `subtitle`: Sottotitolo
- `uppercase`: Maiuscolo

#### **2. Title Block**
```json
"title": {
  "type": "title",
  "settings": {
    "heading_size": "h1"
  }
}
```

#### **3. Price Block**
```json
"price": {
  "type": "price",
  "settings": {}
}
```

#### **4. Variant Picker**
```json
"variant_picker": {
  "type": "variant_picker",
  "settings": {
    "picker_type": "button"
  }
}
```

**Opzioni picker_type:**
- `button`: Pulsanti per varianti
- `dropdown`: Menu a tendina

#### **5. Quantity Selector**
```json
"quantity_selector": {
  "type": "quantity_selector",
  "settings": {}
}
```

#### **6. Buy Buttons**
```json
"buy_buttons": {
  "type": "buy_buttons",
  "settings": {
    "show_dynamic_checkout": true,
    "show_gift_card_recipient": false
  }
}
```

#### **7. Description**
```json
"description": {
  "type": "description",
  "settings": {}
}
```

#### **8. Custom Liquid**
```json
"custom_liquid": {
  "type": "custom_liquid",
  "settings": {
    "custom_liquid": "<div class=\"custom-content\">HTML personalizzato</div>"
  }
}
```

#### **9. Collapsible Content**
```json
"collapsible_content": {
  "type": "collapsible_content",
  "settings": {
    "heading": "Specifiche Tecniche",
    "icon": "clipboard",
    "content": "<p>Contenuto dettagliato delle specifiche</p>",
    "page": ""
  }
}
```

**Icone disponibili:**
- `clipboard`, `car`, `chat_bubble`, `check_mark`, `dryer`, `eye`, `heart`, `iron`, `leaf`, `leather`, `lock`, `map_pin`, `pants`, `peace`, `shirt`, `shoe`, `silhouette`, `snowflake`, `truck`, `washing`

#### **10. Popup**
```json
"popup": {
  "type": "popup",
  "settings": {
    "text": "Informazioni aggiuntive",
    "page": ""
  }
}
```

#### **11. Rating**
```json
"rating": {
  "type": "rating",
  "settings": {}
}
```

### **Impostazioni Media**

```json
"settings": {
  "media_size": "large",           // "small", "medium", "large"
  "media_position": "left",        // "left", "right"
  "gallery_layout": "stacked",     // "stacked", "thumbnail"
  "media_fit": "contain",          // "contain", "cover"
  "image_zoom": "lightbox",        // "lightbox", "hover", "none"
  "mobile_thumbnails": "hide"      // "hide", "show"
}
```

## 🔧 Sezioni Aggiuntive

### **1. Product Recommendations**

```json
"product_recommendations": {
  "type": "product-recommendations",
  "settings": {
    "heading": "Potrebbe interessarti anche",
    "heading_size": "h2",
    "products_to_show": 4,
    "columns_desktop": 4,
    "color_scheme": "scheme-1",
    "image_ratio": "adapt",
    "image_shape": "default",
    "show_secondary_image": false,
    "show_vendor": false,
    "show_rating": false,
    "columns_mobile": "2",
    "padding_top": 36,
    "padding_bottom": 28
  }
}
```

### **2. Collapsible Content (FAQ)**

```json
"collapsible_content": {
  "type": "collapsible-content",
  "blocks": {
    "faq1": {
      "type": "collapsible_row",
      "settings": {
        "heading": "Come posso restituire un prodotto?",
        "icon": "return",
        "row_content": "<p>Puoi restituire il prodotto entro 30 giorni dall'acquisto.</p>",
        "page": ""
      }
    },
    "faq2": {
      "type": "collapsible_row", 
      "settings": {
        "heading": "Quali sono i tempi di spedizione?",
        "icon": "truck",
        "row_content": "<p>Spediamo entro 24-48 ore lavorative.</p>",
        "page": ""
      }
    }
  },
  "block_order": ["faq1", "faq2"],
  "settings": {
    "caption": "",
    "heading": "Domande Frequenti",
    "heading_size": "h1",
    "heading_alignment": "center",
    "layout": "none",
    "color_scheme": "scheme-1",
    "container_color_scheme": "scheme-2",
    "open_first_collapsible_row": false,
    "image_ratio": "adapt",
    "desktop_layout": "image_second",
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **3. Rich Text**

```json
"rich_text": {
  "type": "rich-text",
  "blocks": {
    "heading": {
      "type": "heading",
      "settings": {
        "heading": "Garanzia e Qualità",
        "heading_size": "h2"
      }
    },
    "text": {
      "type": "text",
      "settings": {
        "text": "<p>Tutti i nostri prodotti sono coperti da garanzia di 2 anni.</p>"
      }
    }
  },
  "block_order": ["heading", "text"],
  "settings": {
    "desktop_content_position": "center",
    "content_alignment": "center",
    "color_scheme": "background-2",
    "full_width": true,
    "padding_top": 40,
    "padding_bottom": 52
  }
}
```

### **4. Image with Text**

```json
"image_with_text": {
  "type": "image-with-text",
  "blocks": {
    "heading": {
      "type": "heading",
      "settings": {
        "heading": "Installazione Professionale",
        "heading_size": "h2"
      }
    },
    "text": {
      "type": "text",
      "settings": {
        "text": "<p>Offriamo servizio di installazione con tecnici specializzati.</p>",
        "text_style": "body"
      }
    },
    "button": {
      "type": "button",
      "settings": {
        "button_label": "Richiedi Preventivo",
        "button_link": "/pages/contact",
        "button_style_secondary": false
      }
    }
  },
  "block_order": ["heading", "text", "button"],
  "settings": {
    "image": "shopify://shop_images/installation.jpg",
    "height": "adapt",
    "desktop_image_width": "medium",
    "layout": "text_first",
    "desktop_content_position": "top",
    "desktop_content_alignment": "left",
    "content_layout": "no-overlap",
    "color_scheme": "background-1",
    "image_behavior": "none",
    "mobile_content_alignment": "left",
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **5. Featured Collection**

```json
"featured_collection": {
  "type": "featured-collection",
  "settings": {
    "title": "Prodotti Correlati",
    "heading_size": "h2",
    "description": "",
    "show_description": false,
    "description_style": "body",
    "collection": "related-products",
    "products_to_show": 4,
    "columns_desktop": 4,
    "full_width": false,
    "show_view_all": false,
    "view_all_style": "solid",
    "enable_desktop_slider": false,
    "color_scheme": "background-1",
    "image_ratio": "adapt",
    "image_shape": "default",
    "show_secondary_image": false,
    "show_vendor": false,
    "show_rating": false,
    "enable_quick_add": false,
    "columns_mobile": "2",
    "swipe_on_mobile": false,
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

### **6. Multicolumn**

```json
"multicolumn": {
  "type": "multicolumn",
  "blocks": {
    "column1": {
      "type": "column",
      "settings": {
        "image": "shopify://shop_images/feature1.jpg",
        "title": "Spedizione Gratuita",
        "text": "<p>Su ordini superiori a €50</p>",
        "link_label": "",
        "link": ""
      }
    },
    "column2": {
      "type": "column",
      "settings": {
        "image": "shopify://shop_images/feature2.jpg", 
        "title": "Garanzia 2 Anni",
        "text": "<p>Su tutti i prodotti</p>",
        "link_label": "",
        "link": ""
      }
    }
  },
  "block_order": ["column1", "column2"],
  "settings": {
    "title": "I Nostri Vantaggi",
    "heading_size": "h2",
    "image_width": "third",
    "image_ratio": "adapt",
    "columns_desktop": 2,
    "column_alignment": "center",
    "background_style": "none",
    "button_label": "",
    "button_link": "",
    "color_scheme": "background-1",
    "columns_mobile": "1",
    "swipe_on_mobile": false,
    "padding_top": 36,
    "padding_bottom": 36
  }
}
```

## 🎨 Color Schemes Disponibili

- `scheme-1`: Schema colore 1 (principale)
- `scheme-2`: Schema colore 2
- `scheme-3`: Schema colore 3
- `scheme-4`: Schema colore 4
- `scheme-5`: Schema colore 5

## 📱 Impostazioni Responsive

### Desktop
- `columns_desktop`: 2, 3, 4, 5
- `desktop_content_position`: posizionamento contenuto
- `desktop_image_width`: "small", "medium", "large"
- `media_position`: "left", "right"

### Mobile
- `columns_mobile`: "1", "2"
- `swipe_on_mobile`: true/false
- `mobile_content_alignment`: "left", "center", "right"
- `mobile_thumbnails`: "hide", "show"

## ⚙️ Impostazioni Comuni

### Media e Immagini
```json
"image_ratio": "adapt",        // "adapt", "portrait", "square"
"image_shape": "default",      // "default", "arch", "blob", "chevronleft", "chevronright", "diamond", "parallelogram", "round"
"show_secondary_image": false  // Mostra seconda immagine al hover
```

### Padding e Spaziatura
```json
"padding_top": 36,      // Spaziatura superiore (0-100)
"padding_bottom": 36    // Spaziatura inferiore (0-100)
```

### Dimensioni Heading
- `h0`: Extra Large
- `h1`: Large  
- `h2`: Medium
- `hsmall`: Small

### Layout Options
- `layout`: "image_first", "text_first"
- `content_layout`: "no-overlap", "overlap"
- `background_style`: "none", "primary"

## 💡 Best Practices

1. **Conversioni**: Posiziona elementi di trust sopra il pulsante acquista
2. **Mobile**: Testa sempre la user experience mobile
3. **Performance**: Non caricare troppe immagini pesanti
4. **Trust Building**: Includi garanzie, recensioni, FAQ
5. **Cross-selling**: Usa prodotti correlati strategicamente
6. **Informazioni**: Fornisci tutte le info necessarie per l'acquisto

## ⚠️ Note Importanti

- **Backup**: Fai sempre un backup prima delle modifiche
- **Validazione JSON**: Verifica che il JSON sia valido
- **Testing**: Testa il processo di acquisto completo
- **SEO**: Usa heading appropriati per la SEO
- **Accessibilità**: Assicurati che i contrasti siano sufficienti
- **Performance**: Ottimizza immagini e contenuti per velocità caricamento
