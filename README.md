# Demo AEO + AIEO (TiÃ¡ÂºÂ¿ng ViÃ¡Â»â€¡t)

Website tÃ„Â©nh Ã„â€˜Ã†Â¡n giÃ¡ÂºÂ£n minh hÃ¡Â»Âa cÃƒÂ¡ch triÃ¡Â»Æ’n khai AEO (Answer Engine Optimization)
vÃƒÂ  AIEO (AI Engine Optimization).

## 1) AEO vÃƒÂ  AIEO lÃƒÂ  gÃƒÂ¬?

- AEO: tÃ¡Â»â€˜i Ã†Â°u nÃ¡Â»â„¢i dung Ã„â€˜Ã¡Â»Æ’ cÃƒÂ´ng cÃ¡Â»Â¥ trÃ¡ÂºÂ£ lÃ¡Â»Âi trÃ¡Â»Â±c tiÃ¡ÂºÂ¿p trÃƒÂ­ch xuÃ¡ÂºÂ¥t Ã„â€˜ÃƒÂ¡p ÃƒÂ¡n nhanh, Ã„â€˜ÃƒÂºng ÃƒÂ½ Ã„â€˜Ã¡Â»â€¹nh hÃ¡Â»Âi.
- AIEO: tÃ¡Â»â€˜i Ã†Â°u toÃƒÂ n bÃ¡Â»â„¢ website Ã„â€˜Ã¡Â»Æ’ hÃ¡Â»â€¡ thÃ¡Â»â€˜ng AI hiÃ¡Â»Æ’u ngÃ¡Â»Â¯ cÃ¡ÂºÂ£nh, Ã„â€˜Ã¡Â»â„¢ tin cÃ¡ÂºÂ­y vÃƒÂ  dÃ¡Â»â€¦ tham chiÃ¡ÂºÂ¿u.

## 2) KÃ¡Â»Â¹ thuÃ¡ÂºÂ­t Ã„â€˜ÃƒÂ£ triÃ¡Â»Æ’n khai trong dÃ¡Â»Â± ÃƒÂ¡n nÃƒÂ y

- NÃ¡Â»â„¢i dung dÃ¡ÂºÂ¡ng cÃƒÂ¢u hÃ¡Â»Âi -> cÃƒÂ¢u trÃ¡ÂºÂ£ lÃ¡Â»Âi ngÃ¡ÂºÂ¯n, rÃƒÂµ.
- Semantic HTML5 + heading hÃ¡Â»Â£p lÃƒÂ½.
- Structured data (Schema.org): `WebSite`, `Organization`, `FAQPage`.
- `robots.txt` + `sitemap.xml`.
- `llms.txt` Ã„â€˜Ã¡Â»Æ’ Ã„â€˜Ã¡Â»â€¹nh hÃ†Â°Ã¡Â»â€ºng crawler AI.
- Metadata xÃƒÂ£ hÃ¡Â»â„¢i vÃƒÂ  SEO: title, description, canonical, Open Graph.

## 3) CÃ¡ÂºÂ¥u trÃƒÂºc file

- `index.html`: trang chÃƒÂ­nh, cÃƒÂ³ schema vÃƒÂ  nÃ¡Â»â„¢i dung FAQ.
- `about.html`: thÃƒÂ´ng tin thÃ¡Â»Â±c thÃ¡Â»Æ’/nÃ¡Â»â„¢i dung.
- `styles.css`: giao diÃ¡Â»â€¡n responsive.
- `robots.txt`, `sitemap.xml`, `llms.txt`: hÃ¡Â»â€” trÃ¡Â»Â£ index vÃƒÂ  AI crawl.

## 4) TrÃ†Â°Ã¡Â»â€ºc khi hosting

Domain hiá»‡n táº¡i trong dá»± Ã¡n: `https://tranquoctoan.github.io/aeo-aieo-demo`

- `index.html` (canonical, og:url, JSON-LD url/target)
- `about.html` (canonical)
- `robots.txt` (Sitemap URL)
- `sitemap.xml` (`<loc>`)
- `llms.txt` (Preferred URLs)

## 5) Hosting nhanh

### CÃƒÂ¡ch A: Netlify (khuyÃƒÂªn dÃƒÂ¹ng)

1. TÃ¡ÂºÂ¡o repo GitHub vÃƒÂ  push toÃƒÂ n bÃ¡Â»â„¢ file dÃ¡Â»Â± ÃƒÂ¡n.
2. VÃƒÂ o Netlify -> `Add new site` -> `Import an existing project`.
3. ChÃ¡Â»Ân repo vÃ¡Â»Â«a push.
4. Build command: Ã„â€˜Ã¡Â»Æ’ trÃ¡Â»â€˜ng.
5. Publish directory: `/` (root).
6. Deploy.

### CÃƒÂ¡ch B: GitHub Pages

1. Push project lÃƒÂªn GitHub.
2. VÃƒÂ o `Settings` -> `Pages`.
3. ChÃ¡Â»Ân `Deploy from a branch`.
4. Branch: `main`, folder: `/ (root)`.
5. Save vÃƒÂ  chÃ¡Â»Â URL Pages Ã„â€˜Ã†Â°Ã¡Â»Â£c tÃ¡ÂºÂ¡o.

## 6) Checklist tÃ¡Â»â€˜i Ã†Â°u tiÃ¡ÂºÂ¿p theo

- ViÃ¡ÂºÂ¿t thÃƒÂªm 5-10 bÃƒÂ i theo cÃ¡Â»Â¥m chÃ¡Â»Â§ Ã„â€˜Ã¡Â»Â (topic cluster).
- MÃ¡Â»â€”i bÃƒÂ i cÃƒÂ³ mÃ¡Â»Â¥c "CÃƒÂ¢u trÃ¡ÂºÂ£ lÃ¡Â»Âi nhanh" 40-70 tÃ¡Â»Â« Ã¡Â»Å¸ Ã„â€˜Ã¡ÂºÂ§u bÃƒÂ i.
- LiÃƒÂªn kÃ¡ÂºÂ¿t nÃ¡Â»â„¢i bÃ¡Â»â„¢ giÃ¡Â»Â¯a cÃƒÂ¡c bÃƒÂ i cÃƒÂ¹ng cÃ¡Â»Â¥m.
- GÃ¡ÂºÂ¯n nguÃ¡Â»â€œn tham khÃ¡ÂºÂ£o vÃƒÂ  ngÃƒÂ y cÃ¡ÂºÂ­p nhÃ¡ÂºÂ­t.
- Theo dÃƒÂµi Google Search Console Ã„â€˜Ã¡Â»Æ’ tÃ¡Â»â€˜i Ã†Â°u truy vÃ¡ÂºÂ¥n dÃ¡ÂºÂ¡ng cÃƒÂ¢u hÃ¡Â»Âi.
