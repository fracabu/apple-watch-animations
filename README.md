# ⌚ Apple Watch Animations

**Apple Watch Animations** è un progetto in cui ho replicato le animazioni presenti sulla pagina ufficiale di [Apple Watch Ultra](https://www.apple.com/it/apple-watch-ultra/) utilizzando HTML, CSS e JavaScript. Questo progetto è stato ispirato dal video tutorial di **Marchetti Design**, [Come fare Animazioni Javascript Fade-in allo Scroll (Stile Apple)](https://www.youtube.com/watch?v=COcyWGj6BJ8), che spiega come creare animazioni di tipo fade-in basate sullo scroll.

![image](https://github.com/user-attachments/assets/0d05ad2d-4244-47d4-8a0e-de06488528a9)

## 🎯 Obiettivo del Progetto

L'obiettivo principale di questo progetto è stato esplorare tecniche avanzate di animazione e scrolling per simulare effetti visivi professionali simili a quelli del sito Apple. In particolare:
- Ho utilizzato l'API **Intersection Observer** di JavaScript, come spiegato nel video di Marchetti Design, per monitorare quando gli elementi entrano nella viewport e aggiungere classi CSS per attivare le animazioni.
- Ho creato effetti di **fade-in** su immagini e testo al loro ingresso nello schermo.
- Ho integrato un video di sfondo responsivo per dare maggiore impatto visivo alla pagina.

    ![image](https://github.com/user-attachments/assets/98b93f7e-84d2-4090-8854-c907edd8dc03)

## 📂 Struttura del Progetto

Il progetto contiene i file HTML, CSS e JavaScript necessari per gestire la struttura, lo stile e le animazioni.

```plaintext
apple-watch-animations/
├── .vscode/                        # Configurazioni per l'editor
├── index.html                      # Pagina principale con struttura HTML
├── logo.svg                        # Logo dell'app
├── README.md                       # Documentazione del progetto
├── script.js                       # JavaScript per l'Intersection Observer e le animazioni
├── style.css                       # Stile CSS per il layout e le animazioni
├── video.mp4                       # Video di sfondo utilizzato per la pagina
├── watch.jpg                       # Immagine dell'Apple Watch
└── watch-2.jpg                     # Seconda immagine dell'Apple Watch
```

### Descrizione dei File

- **index.html**: Contiene la struttura principale della pagina e gli elementi HTML che si animano durante lo scroll.
- **style.css**: Include gli stili CSS per il layout e le animazioni, come gli effetti di fade-in.
- **script.js**: Implementa l'API Intersection Observer per aggiungere classi CSS quando gli elementi entrano nella viewport, attivando così le animazioni.
- **video.mp4**: Video di sfondo responsivo che viene mostrato in loop dietro gli elementi.
- **watch.jpg** e **watch-2.jpg**: Immagini utilizzate nella pagina per arricchire il contenuto visivo.

## 🚀 Funzionalità Principali

- **Animazioni al Scroll**: Grazie all'Intersection Observer, gli elementi HTML aggiungono classi CSS al loro ingresso nella viewport, permettendo animazioni sincronizzate con lo scroll.
- **Effetti di Fade-in**: Le immagini e i testi appaiono gradualmente quando sono visibili nella pagina, per un effetto elegante e professionale.
- **Video di Sfondo**: Il video è responsivo e mantiene un aspetto accattivante su diverse dimensioni di schermo, migliorando l’esperienza utente.

## 💻 Come Clonare e Eseguire il Progetto

1. **Clona la Repository**:
   ```bash
   git clone https://github.com/tuo-username/apple-watch-animations.git
   cd apple-watch-animations
   ```

2. **Apri `index.html`**:
   - Apri il file `index.html` nel browser per vedere le animazioni in azione. Non sono necessari server web o dipendenze esterne.

## 🔧 Tecnologie Utilizzate

- **HTML5**: Struttura della pagina e contenuto.
- **CSS3**: Styling avanzato per le animazioni e il layout.
- **JavaScript**: Logica per monitorare lo scroll e attivare le animazioni usando l'Intersection Observer.

## 🛠️ Possibili Miglioramenti

Essendo un progetto didattico, ci sono alcune funzionalità aggiuntive che potrebbero essere implementate per esercitarsi ulteriormente:

- **Animazioni Addizionali**: Aggiungere altri effetti, come lo zoom e il parallax, per animazioni più complesse.
- **Modalità Scura**: Implementare un tema scuro per migliorare l’esperienza visiva.
- **Ottimizzazione Performance**: Utilizzare tecniche di lazy loading per migliorare il caricamento di immagini e video.

## 📚 Risorse Utili

- [Video di Marchetti Design - Come fare Animazioni Javascript Fade-in allo Scroll (Stile Apple)](https://www.youtube.com/watch?v=COcyWGj6BJ8)
- [Guida all'Intersection Observer API](https://developer.mozilla.org/en-US/docs/Web/API/Intersection_Observer_API)
- [CSS Animations su MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations)
- [Video di Sfondo in HTML5](https://css-tricks.com/full-page-background-video-styles/)

---

Grazie per aver esplorato **Apple Watch Animations**! Questo progetto, ispirato al video di Marchetti Design, mi ha permesso di esercitarmi con animazioni avanzate e gestione di contenuti visivi dinamici con JavaScript.



