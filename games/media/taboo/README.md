# Galleria foto/video — Taboo

Per aggiungere una foto o un video alla galleria mostrata dal proiettore:

1. Copia il file (jpg, png, mp4, webm...) in questa cartella.
2. Apri `games/taboo.html`, trova l'array `MEDIA_ITEMS` (vicino all'inizio dello `<script>`) e aggiungi una riga, ad esempio:

```js
const MEDIA_ITEMS = [
  { file:'media/taboo/foto1.jpg', caption:'Il giorno della laurea' },
  { file:'media/taboo/video1.mp4', caption:'Bruxelles 2023' },
];
```

3. Fai commit e push: la galleria è pronta, richiamabile in qualsiasi momento con il pulsante 🖼️ nello schermo del conduttore.
