# FCF Stats

Estadístiques de plantilla per a qualsevol equip de la Federació Catalana de Futbol (fcf.cat).

## Funcionalitats

- 🔍 Cerca qualsevol equip de qualsevol competició de fcf.cat
- ⚡ Caché de 24h via Supabase (resultats instantanis en consultes repetides)
- 🕓 Historial de les últimes 15 cerques
- 📊 Dashboard complet: Conv/Tit/Sup/PJ/Gols/G·P/Grogues/Vermelles/2G
- 🖨 Exportació a PDF i CSV

## Tecnologia

- HTML/JS estàtic (sense framework)
- Supabase (PostgreSQL) per a caché i historial
- Desplegat a Vercel

## Supabase

- Project URL: `https://msbfqqvquxvieyiyqlen.supabase.co`
- Taules: `team_cache`, `search_history`
- Caché TTL: 24 hores

## Ús

1. Obre l'app
2. Copia la URL de la pàgina de classificació de fcf.cat
3. Selecciona l'equip
4. Genera el dashboard (~10 segons primera vegada, instantani si hi ha caché)
