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

Banyak bet yang nanya tutor... 
Gini bang
1. Browser pastikan pake vpn us soalnya tentara nya harus tentara amrik
2. masuk ke https://chatgpt.com/veterans-claim terus klik verify
3. udahan klik verify, isi data nah datanya ambil dari json itu
4. kalau gada branch, ke gemini itu udah ada json key geminiquery tinggal copy
5. setelah verify itu nanti akan ada email baru
6. klik aja emailnya
7. bayar (disini lu masukin cc lu, kalo ga punya cc (kayak gw) pake aja cc aplikasi jago), 0 rupiah koq awowkwkw setaun guys lumayan njr
8. Kalo ada pesan we know you entusias of this program blabla artinya udah ada yang claim pake veteran itu
9. usahain akun baru aja, bikin pake outlook itu ga ribet kaya google.

buat yang rakus, bisa pake https://github.com/ThanhNguyxn/SheerID-Verification-Tool/ tapi format json nya harus lu ubah dulu ya.
