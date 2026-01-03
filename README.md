# vets

Dataset exports from Find a Grave with branch-of-service enrichment prompts.

Files:
- `findagrave copy 2_gem.json`: Records with `geminiQuery` added when `branch` is empty.

Notes:
- JSON is an array of records with fields like `firstName`, `lastName`, `branch`,
  `birthDate`, `dischargeDate`, and `link`.

1. Data di ekstrak dari findagrave
2. Saya ekstrak yang mati muda, supaya veteran yang udah tuir ga ketarik juga
3. Beberapa nama depan ada pangkatnya tapi beberapa udah saya bersiin takutnya ada yang ketinggalan, misal CPT Prabowo, nah cpt itu berati captain jadi jgn lu masukin jadi nama depan juga ya
4. Beberapa data branch of service nya kosong, tapi setiap branch of service kosong itu udah saya kasih key "geminiQuery", itu lu copy aja paste ke gemini nanti dia kasih branch of servicenya. Soalnya bot gw di blokir sama cloudflare guys awowkwkw
5. VPN pake USA
