### 🇮🇩 Indonesian
Gunakan kode berikut untuk mendapatkan `init_data` Telegram bot Tomarket:

```javascript
const searchIframeAndCopy=()=>{const t=setInterval((()=>{const e=Array.from(document.getElementsByTagName("iframe")).find((t=>t.src.includes("https://mini-app.tomarket.ai/#")));if(e){clearInterval(t);const a=e.src.replace("https://mini-app.tomarket.ai/#tgWebAppData=","");navigator.clipboard.writeText(a).then((()=>{alert("Init data berhasil disalin ke clipboard! Tempelkan ke bot @Tomarket_ai_bot.")}))["catch"]((()=>{alert("Salin init data berikut ini secara manual:\n\n"+a)}))}}),1e3)};alert("Silakan jalankan bot Tomarket Anda. Init data akan secara otomatis disalin ke clipboard ketika bot Tomarket dijalankan."),searchIframeAndCopy();
```

## Bagaimana Cara Mendapatkan Init Data?

Salin kode diatas. Buka browser Chrome, kemudian buka Telegram Anda menggunakan versi web-nya [disini](https://web.telegram.org). Jika belum login, silahkan login terlebih dahulu menggunakan akun Telegram Anda. Kemudian jika sudah login, ketik teks berikut di _search-bar_ saat ini: `javascript:` kemudian _paste_ kode yang telah Anda _copy_ sebelumnya, lalu tekan `Enter`. Jika muncul pesan:

```txt
Silakan jalankan bot Tomarket Anda. Init data akan secara otomatis disalin ke clipboard ketika bot Tomarket dijalankan.
```

berarti kode berhasil dijalankan. Lanjut buka bot Tomarket Anda. `init_data` akan tersalin ke clipboard secara otomatis. Jika sudah tersalin, lanjut ke instruksi [penggunaan](./README.md#penggunaan).

---

### 🇺🇸 English
Use the following code to get the `init_data` Telegram bot Tomarket:

```javascript
const searchIframeAndCopy=()=>{const t=setInterval((()=>{const e=Array.from(document.getElementsByTagName("iframe")).find((t=>t.src.includes("https://mini-app.tomarket.ai/#")));if(e){clearInterval(t);const a=e.src.replace("https://mini-app.tomarket.ai/#tgWebAppData=","");navigator.clipboard.writeText(a).then((()=>{alert("Init data successfully copied to clipboard! Paste it into @Tomarket_ai_bot bot.")}))["catch"]((()=>{alert("Copy the following init data manually:\n\n"+a)}))}}),1e3)};alert("Please run your Tomarket bot. Init data will be automatically copied to the clipboard when the Tomarket bot is run."),searchIframeAndCopy();
```

## How to Get Init Data?

Copy the code above. Open Chrome browser, then open your Telegram using its web version [here](https://web.telegram.org). If you are not logged in, please login first using your Telegram account. Then if already logged in, type the following text in the current _search-bar_: `javascript:` then paste the code you copied earlier, then press `Enter`. If the message appears:

```txt
Please run your Tomarket bot. Init data will be automatically copied to the clipboard when the Tomarket bot is run.
```

means the code was executed successfully. Continue to open your Tomarket bot. The `init_data` will be copied to the clipboard automatically. If it is copied, go to the [usage](./README.md#usage) instruction.
