# Bacheca – BBS via telnet

Rubrica e terminale ANSI (80 colonne, CP437, colori VGA) per visitare le BBS ancora attive direttamente dal browser, anche da smartphone.

- Elenco di BBS attive (fonte: [Telnet BBS Guide](https://www.telnetbbsguide.com)), ricerca, filtro per software, preferite, BBS personali
- Connessione tramite ponte WebSocket → telnet (predefinito: `wss://telnet-proxy.fly.dev/`, configurabile; self-hosting con `npx telnet-proxy`)
- Supporto WebSocket diretto per le BBS che lo offrono
- Barra tasti per mobile (Esc, frecce, Tab, Ctrl+C)

Il telnet viaggia in chiaro: usa sulle BBS password che non usi altrove.

Autore: Pony10
