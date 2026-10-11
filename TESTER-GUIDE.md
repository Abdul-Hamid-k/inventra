# Varnix test version: guide for testers

Thank you for testing Varnix! This is a **test version** of the full shop app: billing, stock, customers, credit (udhaar), GST reports and backups. It works without internet.

Website: **https://varnix-license-server.vercel.app**

## 1. Download

Open the download page and choose your device (x.y.z is the version number, for example 0.13.0):

**https://github.com/Abdul-Hamid-k/varnix/releases/latest**

| Device | File |
|---|---|
| Windows computer (Windows 10 or 11) | `Varnix-Setup-x.y.z.exe` |
| Android phone or tablet (Android 7 or newer) | `Varnix-x.y.z.apk` |
| User manual | `Varnix-User-Manual.pdf` (English), `Varnix-User-Manual-Hindi.pdf` (हिन्दी) |

## 2. Install

### Windows

1. Open `Varnix-Setup-x.y.z.exe`.
2. Windows may show **"Windows protected your PC"**. This is normal for a test version. Click **More info**, then **Run anyway**.
3. Follow the steps (Next → Install → Finish). Varnix opens.

### Android

1. Open `Varnix-x.y.z.apk` from your downloads.
2. If the phone asks, allow **Install unknown apps** for your browser or file app, then tap **Install**.
3. If Play Protect warns you, tap **More details → Install anyway**.

## 3. Start

1. **Register your shop**: owner's name, shop name, mobile number and city (email is optional). Tick **I agree to the Terms of service · Privacy notice**. You need internet only for this step. Your **15-day free trial of everything** starts.
2. **First-time setup**: store details and the owner's PIN. Choose **Start fresh** for your real shop, or **Explore with demo data** to look around first (remove the demo data later from the dashboard).
3. Start billing.

**After the 15 days** Varnix keeps working on the **Free plan**, with no time limit: one device, the owner only, with billing, GST bills, stock, customers and reports. Staff, sync, Google Drive backup, the WhatsApp report and AI need a paid plan. Your data stays as it is.

## 4. What to try

Please use Varnix the way you run your shop, and try as many of these as you can:

**Billing**
- [ ] Add 10 or more of your products (with GST rate and stock). Try loose goods sold by weight (kg) or volume (ltr).
- [ ] Make bills at the counter: search, barcode scan (camera on phones), discounts, cash / UPI / card, and **On credit (udhaar)**.
- [ ] Hold a bill (give it a name like "Table 3") and finish it later.
- [ ] Print a bill or share it as PDF on WhatsApp.
- [ ] Return an item, and void a wrong bill (owner).

**Credit (udhaar) and advance**
- [ ] Put a bill on credit for a customer, then collect the due later in Sales.
- [ ] For a customer who owes money, take **more than the bill** at the counter: the payment window shows their old dues. Try **Clear old dues**, **keep the rest as advance**, and **Give back as change**.
- [ ] Use **Use advance** to pay a later bill. On the customer page, try **Add advance**, **Use on dues** and **Give back** (owner).
- [ ] Check the dashboard's **Credit (udhaar) to collect** and send a **WhatsApp reminder** (Settings → Billing & tax → Credit reminders sets the days).

**Stock and suppliers**
- [ ] Add stock, record damaged or expired stock.
- [ ] Add a supplier, make a purchase order and **send it on WhatsApp**; receive the stock.
- [ ] Look at **Smart alerts**: reorder suggestions, items already on order, credit overdue.

**Reports**
- [ ] Reports → Daily report: does the **Cash drawer summary** match the money you took today?
- [ ] Reports → GST return. Switch **Include in GST report** off for one bill and check it is left out.

**Staff (paid plans and the trial)**
- [ ] Add a staff user and a supervisor, each with their own PIN. Check what staff can and cannot do.
- [ ] Settings → Users & access → **Staff changes need approval**: as staff, edit a product price, a bill or a customer; as owner, approve it from the dashboard.

**Phone and computer (Smart and Business)**
- [ ] Settings → Sync → **Add a device**, scan the code on the phone. Bill on one, check it appears on the other.

**Everything else**
- [ ] Take a backup (Backup → Back up now). On a phone, share it to yourself.
- [ ] Change the language (हिन्दी, मराठी, ગુજરાતી, தமிழ், తెలుగు) and try dark mode. Tell us any word that stays in English.
- [ ] On a phone: use the **Back** button between pages; on Home it should ask before closing.

## 5. Tell us what you found

In Varnix, open **Contact us** (Settings → Contact us, or click your initials at the top right), choose **Get help**, then **Chat on WhatsApp** or **Email us**. Your shop name and device ID are added to the message automatically.

Or email **abdulhamidk0172@gmail.com** (Monday to Saturday, 10 am – 7 pm).

Please tell us:

- what you were doing,
- what happened, and what you expected,
- a screenshot if you can.

Everything is useful: bugs, confusing screens, missing features, wrong translations.

## Good to know

- **Your data stays on your device.** It is encrypted and never sent to us. Only your registration details (name, shop, phone, city) reach us. Keep your **recovery key** (Backup page) somewhere safe.
- **Updates:** when a new version is out, Varnix shows "Update available". Install it over the old one; your data stays. If you use phone and computer together, update both.
- **Plans** (one-time, including GST): **Free** after the trial (1 device, owner only) · **Starter ₹2,999** (2 devices, 3 staff) · **Smart ₹4,999** (5 devices, sync, Drive backup, sales forecast; first year of cloud free, then ₹999 a year) · **Business ₹8,999** (10 devices, all AI, more shops). Launch offer: the first 100 shops get Smart for ₹2,999. Full refund within 7 days. Details: https://varnix-license-server.vercel.app/pricing
- **Buying:** use Contact us → Buy a licence (WhatsApp or email). We send a licence key; type it in Settings → About → Activate licence.
- **Trial longer than 15 days?** Ask us through Contact us. We can extend it.
- **Coming soon:** Google Drive backup.
- **Android:** from 0.4.2 on, every update (and the Play Store version later) installs over the app; your data stays.
- **Varnix used to be called Inventra.** Same app, new name and logo.

## Moving to 0.4.2 on Android (one time)

Only if your phone has Varnix **0.4.1 or older**. Version 0.4.2 is signed with Varnix's own key, so the phone will not install it over the old app. Your data moves with a backup:

1. In Varnix, open **Backup** and tap **Back up now**.
2. Tap the **share** icon on that backup and send it to yourself (WhatsApp "Message yourself", Google Drive or email).
3. Next to **Recovery key**, tap **Reveal**, then **Copy**. Paste it into the same chat or a note **within 60 seconds** (it is cleared from the clipboard after that). You need these 64 characters to open the backup on the new app.
4. Uninstall Varnix (long-press the icon → Uninstall).
5. Install the new `Varnix-x.y.z.apk` and register with **the same mobile number**.
6. During setup choose **Start fresh**, then open **Backup → Restore from file** and pick the backup you sent yourself (download it from WhatsApp or Drive first).
7. When Varnix asks, tap **Enter recovery key** and paste the key. Your products, bills and customers are back.

Stuck? Contact us → Chat on WhatsApp. Please don't uninstall before steps 1 to 3 are done; uninstalling deletes the data on the phone.
