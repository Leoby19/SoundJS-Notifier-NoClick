## Nome della Libreria: SoundJS-Notifier-NoClick

### Descrizione

**Italiano:**

La libreria SoundJS-Notifier-NoClick è un modulo JavaScript che consente agli sviluppatori di integrare facilmente notifiche sonore nei loro progetti web, indipendentemente dal browser utilizzato o dalla versione del browser stesso. Questa libreria supporta tutti i principali browser e funziona su qualsiasi sistema operativo. Offre una soluzione semplice per migliorare l'esperienza dell'utente attraverso notifiche audio, sia per scopi informativi che per interazioni significative. Un aspetto importante è che permette di avviare un suono di notifica senza la necessità di un click fisico sulla pagina, raggirando l'autoplay su tutti i browser.

**English:**

SoundJS-Notifier-NoClick is a JavaScript library that allows developers to easily integrate notification sounds into their web projects, regardless of the browser or its version. This library supports all major browsers and works on any operating system. It provides a straightforward solution to enhance the user experience with audio notifications, both for informational purposes and meaningful interactions. An important feature is that it allows triggering a notification sound without the need for a physical click on the page, bypassing autoplay restrictions on all browsers.

### Funzionalità

**Italiano:**

- Facile integrazione con un'unica funzione JavaScript.
- Supporto per tutti i principali browser (Chrome, Firefox, Safari, Edge, ecc.).
- Compatibile con qualsiasi versione di browser.
- Funzionamento su qualsiasi sistema operativo.
- Personalizzazione dei suoni delle notifiche.

**English:**

- Easy integration with a single JavaScript function call.
- Support for all major browsers (Chrome, Firefox, Safari, Edge, etc.).
- Compatibility with any browser version.
- Works on any operating system.
- Customizable notification sounds.

### Come Utilizzare

**Italiano:**

1. Includi la libreria nel tuo progetto:

```html
<script src="SoundJS-Notifier-NoClick.js"></script>
```

2. Chiamata alla funzione per generare il popup di accettazione delle notifiche sonore:

```javascript
createPopupEnableSounds("media/sound.mp3");
```

3. Chiamata alla funzione per riprodurre una notifica sonora:

```javascript
crossBrowserNotificationSoundPlay();
```

**English:**

1. Include the library in your project:

```html
<script src="SoundJS-Notifier-NoClick.js"></script>
```

2. Call the function to generate the sound notifications acceptance popup:

```javascript
createPopupEnableSounds("media/sound.mp3");
```

3. Call the function to play a notification sound:

```javascript
crossBrowserNotificationSoundPlay();
```

### Esempio

**Italiano:**

```html
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pagina Web</title>
</head>
<body>
  <div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
    Prova a lanciare la funzione dalla console non avrai piu problemi di click! <br>
    crossBrowserNotificationSoundPlay() in console!
  </div>
</body>
<script src="SoundJS-Notifier-NoClick.js"></script>
<script>

    window.onload = function() {
        createPopupEnableSounds("media/sound.mp3");
    };

</script>
</html>
```

**English:**

```html
<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Web Page</title>
</head>
<body>
  <div style="display: flex; justify-content: center; align-items: center; height: 100vh;">
    Try running the function from the console, you won't have any more click issues!<br>
    crossBrowserNotificationSoundPlay() in console!
  </div>
</body>
<script src="SoundJS-Notifier-NoClick.js"></script>
<script>

    window.onload = function() {
        createPopupEnableSounds("media/sound.mp3");
    };

</script>
</html>
```

### Contribuire

Per contribuire al progetto, segui questi passaggi:

1. Forka il repository.
2. Crea un branch per il tuo contributo: `git checkout -b nuova-funzionalita`
3. Fai i tuoi cambiamenti e commit: `git commit -m "Aggiunta nuova funzionalità"`
4. Pusha il tuo branch: `git push origin nuova-funzionalita`
5. Invia una Pull Request nella branch `main` del repository originale.

### Licenza

Questo progetto è concesso in licenza sotto la [Licenza MIT](LICENSE).

### Autore

[@Leoby19](https://github.com/Leoby19)

### Contatti

Per domande o supporto, puoi contattare l'autore tramite email: leonardo@menumal.it.
