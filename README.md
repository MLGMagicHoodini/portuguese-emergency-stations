# 🚒 Portuguese Emergency Stations / Estações de Emergência em Portugal

**🌐 Live site / Site:** https://mlgmagichoodini.github.io/portuguese-emergency-stations/

**✉️ Suggest a change / Sugerir uma alteração:** https://forms.gle/REHkKJc9ij5ECTV97

---

## English

A community-built map of fire stations, police stations, hospitals, health centres and other emergency-service locations in Portugal, including the Azores and Madeira, with the vehicles based at each one (ID, type, plate, year, photos and history).

The data is collected by volunteers from visits and public sources. It may be incomplete or out of date, and it is **not an official source**. In an emergency, call **112**.

### How it works
The site is a single static page (`index.html`) that reads its data from simple spreadsheet files:

| File | Contents |
|---|---|
| `stations.csv` | One row per station: category, name, address, contacts, coordinates, tags, description |
| `vehicles.csv` | One row per vehicle, linked to a station by `station_id` |
| `categories.csv` | Station categories (hospital, fire station, school…) |
| `types.csv` | Names for vehicle type codes (VUCI, ABSC…) |
| `tags.csv` | Translations for tags (e.g. `sapadores`) |

To add or fix something, edit the CSV files and commit. The site updates by itself.

### Contributing
Use the suggestion form above to add a station, correct information, add a vehicle or photo, or report a problem. Suggestions are reviewed before they appear.

- Please mention where the information comes from.
- Photos must be your own or used with permission, and are shown with credit.
- **No personal information about staff.** Stations and vehicles only.

Map data © OpenStreetMap contributors.

---

## Português

Um mapa feito pela comunidade com quartéis de bombeiros, esquadras, hospitais, centros de saúde e outros locais de emergência em Portugal, incluindo os Açores e a Madeira, com os veículos de cada um (ID, tipo, matrícula, ano, fotos e historial).

Os dados são recolhidos por voluntários, através de visitas e fontes públicas. Podem estar incompletos ou desatualizados e **não são uma fonte oficial**. Em caso de emergência, ligue **112**.

### Como contribuir
Use o formulário de sugestões acima para adicionar uma estação, corrigir informação, adicionar um veículo ou foto, ou reportar um problema. As sugestões são revistas antes de aparecerem.

- Indique de onde vem a informação.
- As fotos têm de ser suas ou usadas com permissão, e são mostradas com crédito.
- **Sem dados pessoais de pessoas.** Apenas estações e veículos.

Dados do mapa © colaboradores do OpenStreetMap.
