# Spendpin: is my data safe?

[English](#english) · [Bahasa Melayu](#malay) · [中文](#chinese)

Short answers to the questions people ask most, and **three ways to check them yourself**, without having to trust us. The full details are in the [Privacy Policy](./).

---

## English {#english}

### Does Spendpin upload my expenses or captured payments?
No. **Spendpin has no server.** There is no Spendpin account and no Spendpin database on the internet, so there is nowhere for your records to be sent. Your expenses and captured payments are stored only on your phone. Even the developer cannot see them.

The only copy outside your phone is your phone's own Google backup, which Spendpin allows only when it is end-to-end encrypted with your screen lock. Google cannot read it, and neither can we.

### Can Spendpin read my WhatsApp or other chats?
To read payment alerts, Android's "notification access" shows Spendpin every new notification. Spendpin ignores any notification that is not from these payment apps the moment it arrives, without reading or saving it: TNG eWallet, MAE (Maybank), CIMB OCTO, Grab, ShopeePay, Boost, MyPB (Public Bank) and Ryt Bank.

### Can Spendpin take my money?
No. Spendpin cannot log in to your e-wallet or bank, cannot tap buttons in other apps, and cannot read your SMS or OTP codes. It does not have those permissions, and Android would show them if it did (see check 1 below).

### Why does it run in the background?
Only to catch payment alerts the moment they arrive. Android keeps it running only if you turn on auto-capture. It also notes when your phone loses internet, so it can warn you afterwards that payment alerts may have been missed. That stays on your phone. Auto-capture is optional: the rest of the app works without it, and you can switch it off at any time.

### What does go online?
- **Ads** from Google AdMob. Google gets normal device information to show ads, the same as in any free app. It **never** gets your expenses, amounts, notes or notifications.
- **Exchange rates** and the **Bank Negara OPR**: Spendpin downloads public figures. Nothing of yours is sent.
- **AI (only if you add your own Google Gemini key):** what you type to Pin or Quick Add, or a receipt you scan, goes to Google under your own key. Captured notifications are **never** sent to the AI.

### Check it yourself
1. **Permissions:** Settings → Apps → Spendpin → Permissions. Android itself shows this screen; an app cannot fake it. You will see only *Notifications*: no SMS, contacts, location, camera or microphone.
2. **Every connection:** install the free app **PCAPdroid** from Google Play (no root needed) and use Spendpin for a while. It lists every server each app talks to. Spendpin connects only to Google (ads), `open.er-api.com` (exchange rates), `api.bnm.gov.my` (OPR), `leonokh.github.io` (to check whether an update is required), and `generativelanguage.googleapis.com` if you use AI with your own key.
3. **Airplane mode:** turn it on and use Spendpin as usual: add expenses, check budgets and reports. Everything still works, because your records live on your phone, not on a server.

### How do I stop it or delete everything?
- **Stop capture:** Android Settings → Notifications → Notification access → switch Spendpin off.
- **Delete everything:** Spendpin Settings → **Delete My Data**, or uninstall the app.

Questions: **leonapp2625@gmail.com**

---

## Bahasa Melayu {#malay}

### Adakah Spendpin memuat naik perbelanjaan atau pembayaran yang ditangkap?
Tidak. **Spendpin tiada pelayan.** Tiada akaun Spendpin dan tiada pangkalan data Spendpin di internet, jadi rekod anda tidak ada tempat untuk dihantar. Perbelanjaan dan pembayaran yang ditangkap disimpan di telefon anda sahaja. Pembangun pun tidak dapat melihatnya.

Satu-satunya salinan di luar telefon ialah sandaran Google telefon anda sendiri, yang dibenarkan oleh Spendpin hanya jika ia disulitkan hujung ke hujung dengan kunci skrin anda. Google tidak dapat membacanya, begitu juga kami.

### Bolehkah Spendpin membaca WhatsApp atau sembang lain?
Untuk membaca makluman pembayaran, "akses pemberitahuan" Android menunjukkan setiap pemberitahuan baharu kepada Spendpin. Spendpin mengabaikan pemberitahuan yang bukan daripada aplikasi pembayaran ini sebaik sahaja ia tiba, tanpa membaca atau menyimpannya: TNG eWallet, MAE (Maybank), CIMB OCTO, Grab, ShopeePay, Boost, MyPB (Public Bank) dan Ryt Bank.

### Bolehkah Spendpin mengambil wang saya?
Tidak. Spendpin tidak boleh log masuk ke e-dompet atau bank anda, tidak boleh menekan butang dalam aplikasi lain, dan tidak boleh membaca SMS atau kod OTP anda. Ia tiada kebenaran itu, dan Android akan menunjukkannya jika ada (lihat semakan 1 di bawah).

### Kenapa ia berjalan di latar belakang?
Hanya untuk menangkap makluman pembayaran sebaik sahaja ia tiba. Android membiarkannya berjalan hanya jika anda menghidupkan tangkapan automatik. Ia juga mencatat bila telefon anda hilang internet, supaya boleh memberi amaran selepas itu bahawa makluman pembayaran mungkin terlepas. Catatan itu kekal di telefon anda. Tangkapan automatik adalah pilihan: aplikasi lain berfungsi tanpanya, dan anda boleh mematikannya bila-bila masa.

### Apa yang dihantar ke internet?
- **Iklan** daripada Google AdMob. Google mendapat maklumat peranti biasa untuk memaparkan iklan, sama seperti mana-mana aplikasi percuma. Ia **tidak pernah** mendapat perbelanjaan, jumlah, nota atau pemberitahuan anda.
- **Kadar pertukaran** dan **OPR Bank Negara**: Spendpin memuat turun angka awam. Tiada maklumat anda dihantar.
- **AI (hanya jika anda menambah kunci Google Gemini anda sendiri):** apa yang anda taip kepada Pin atau Tambah Pantas, atau resit yang anda imbas, dihantar ke Google di bawah kunci anda sendiri. Pemberitahuan yang ditangkap **tidak pernah** dihantar ke AI.

### Semak sendiri
1. **Kebenaran:** Tetapan → Aplikasi → Spendpin → Kebenaran. Skrin ini ditunjukkan oleh Android sendiri; aplikasi tidak boleh memalsukannya. Anda hanya akan melihat *Pemberitahuan*: tiada SMS, kenalan, lokasi, kamera atau mikrofon.
2. **Setiap sambungan:** pasang aplikasi percuma **PCAPdroid** dari Google Play (tidak perlu root) dan guna Spendpin seketika. Ia menyenaraikan setiap pelayan yang dihubungi oleh setiap aplikasi. Spendpin hanya menyambung ke Google (iklan), `open.er-api.com` (kadar pertukaran), `api.bnm.gov.my` (OPR), `leonokh.github.io` (untuk menyemak sama ada kemas kini diwajibkan), dan `generativelanguage.googleapis.com` jika anda guna AI dengan kunci anda sendiri.
3. **Mod pesawat:** hidupkannya dan guna Spendpin seperti biasa: tambah perbelanjaan, semak bajet dan laporan. Semuanya tetap berfungsi, kerana rekod anda disimpan di telefon anda, bukan di pelayan.

### Bagaimana untuk menghentikan atau memadam semuanya?
- **Hentikan tangkapan:** Tetapan Android → Pemberitahuan → Akses pemberitahuan → matikan Spendpin.
- **Padam semuanya:** Tetapan Spendpin → **Padam Data Saya**, atau nyahpasang aplikasi.

Soalan: **leonapp2625@gmail.com**

---

## 中文 {#chinese}

### Spendpin 会上传我的支出或自动记录的付款吗？
不会。**Spendpin 没有服务器。** 没有 Spendpin 账号，网上也没有 Spendpin 数据库，所以你的记录根本没有地方可以传。支出和自动记录的付款只存在你的手机里，连开发者也看不到。

手机以外唯一的副本是你手机自己的 Google 备份，而且 Spendpin 只在备份用你的屏幕锁做端到端加密时才允许备份。Google 读不了，我们也读不了。

### Spendpin 能看我的 WhatsApp 或其他聊天吗？
为了读取付款通知，Android 的“通知使用权”会把每条新通知都交给 Spendpin。凡不是来自以下付款应用的通知，Spendpin 一收到就忽略，不读取也不保存：TNG eWallet、MAE（Maybank）、CIMB OCTO、Grab、ShopeePay、Boost、MyPB（Public Bank）和 Ryt Bank。

### Spendpin 能拿走我的钱吗？
不能。Spendpin 无法登录你的电子钱包或银行，无法点击其他应用里的按钮，也无法读取你的短信或 OTP 验证码。它没有这些权限；如果有，Android 会显示出来（见下面的检查 1）。

### 为什么它在后台运行？
只是为了在付款通知一出现时就记录下来。只有你开启自动记录，Android 才会让它在后台运行。它也会记下手机什么时候断网，以便之后提醒你可能漏掉了付款通知；这个记录只留在手机里。自动记录是可选的：不开也能用其他功能，随时可以关掉。

### 哪些内容会上网？
- **广告**：来自 Google AdMob。Google 会获得一般的设备信息来显示广告，和任何免费应用一样。它**绝不会**拿到你的支出、金额、备注或通知。
- **汇率**和**国家银行 OPR**：Spendpin 只是下载公开数据，不会发送你的任何信息。
- **AI（只有在你加入自己的 Google Gemini 密钥后）**：你对 Pin 或快速记账输入的内容、你扫描的收据，会用你自己的密钥发送给 Google。自动记录的通知**绝不会**发给 AI。

### 自己检查
1. **权限**：设置 → 应用 → Spendpin → 权限。这个页面由 Android 系统显示，应用无法伪造。你只会看到*通知*，没有短信、通讯录、位置、相机或麦克风。
2. **所有连接**：从 Google Play 安装免费应用 **PCAPdroid**（不需要 root），然后使用 Spendpin 一段时间。它会列出每个应用连接的所有服务器。Spendpin 只连接 Google（广告）、`open.er-api.com`（汇率）、`api.bnm.gov.my`（OPR）、`leonokh.github.io`（检查是否必须更新），以及你用自己的密钥使用 AI 时的 `generativelanguage.googleapis.com`。
3. **飞行模式**：开启后照常使用 Spendpin：记账、查看预算和报表。一切照常运作，因为你的记录存在手机里，不在服务器上。

### 怎样停止或删除所有数据？
- **停止自动记录**：Android 设置 → 通知 → 通知使用权 → 关闭 Spendpin。
- **删除所有数据**：Spendpin 设置 → **删除我的数据**，或卸载应用。

有问题请联系：**leonapp2625@gmail.com**
