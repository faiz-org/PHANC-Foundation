A4APPLE WEBSITE — GITHUB PE DAALNE KA TAREEKA (Roman Urdu)

Is folder ki files: index.html + story/programme/preschool/impact/events/donate/contact.html, style.css, app.js,
content.json (poora text), uploads/ (aapki photos yahan save hongi), robots.txt, sitemap.xml, .nojekyll

STEP 1 — GitHub par daalna
1. github.com par account banayein -> New repository -> naam e.g. a4apple -> Public -> Create.
2. "uploading an existing file" par click karein, is ZIP ke andar ki SAARI files (aur uploads folder) drag karein -> Commit changes.
3. Settings -> Pages -> Source: "Deploy from a branch" -> Branch: main, folder: /(root) -> Save.
4. 1-2 minute baad aapki site is link par hogi: https://USERNAME.github.io/a4apple/

STEP 2 — Sirf aapka edit access (token)
1. GitHub -> profile photo -> Settings -> Developer settings -> Personal access tokens -> Fine-grained tokens -> Generate new token.
2. Repository access: "Only select repositories" -> sirf a4apple. Permissions -> Repository permissions -> Contents: Read and write.
3. Expiration: 1 year. Generate -> token copy karein (sirf ek baar dikhta hai; kahin safe likh lein, kisi ko na dein).
4. Apni website kholein -> neeche footer mein chhota "Admin" -> username, repo name (a4apple), branch (main), token paste -> Connect.
5. Ab neeche "✏️ Edit site" aayega. Text par tap karke likhein, photo ke upar 📷 se photo badlein, 🎨 se art badlein.
   Donate page par UPI ID, bank details aur apna QR upload karein. Phir "Save & publish". 1-2 minute mein sab ko dikhega.
Doosre log Admin kholen bhi to token ke baghair kuch save nahi kar sakte.

STEP 3 — Google par online
1. search.google.com/search-console -> Add property -> "URL prefix" -> apni site ka link.
2. Verification: "HTML tag" chunein -> jo <meta ...> tag mile, GitHub mein har .html file mein "Google Search Console" wale comment ki jagah paste karein (ya mujhse kahein, main kar dunga).
3. sitemap.xml aur robots.txt mein USERNAME aur REPO ko apne asli naam se badlein (GitHub par file kholkar pencil icon se).
4. Search Console -> Sitemaps -> sitemap.xml submit. Google ko index karne mein kuch din lag sakte hain.
Apna domain (a4apple.org) ho to: Settings -> Pages -> Custom domain.

NOTES
- Token sirf aapke phone/computer ke browser mein rehta hai. Phone kho jaye to GitHub se token delete (revoke) kar dein.
- Bacchon ki photos daalne se pehle parents ki permission zaroor lein.
