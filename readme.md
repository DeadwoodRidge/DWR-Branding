# Deadwood Ridge Branding

Publieke branding assets voor gebruik in Discord webhooks en Rich Presence.

> ⚠️ Let op: deze repo bevat alleen **afbeeldingen** die publiek gedeeld mogen worden.  
> Alle gevoelige code en configs staan in de private core repo.

---

## 📂 Structuur

branding/
│
├── dwr_logo.png # Author icon in Discord embeds (256x256 of 512x512)
├── dwr_footer.png # Klein icoon in footer (32x32 of 64x64)
├── dwr_avatar.png # Avatar van de webhook (128x128 of 256x256)
├── dwr_banner.png # Optionele brede banner onderaan embed (800x200 of 1200x400)
└── dwr_thumb.png # Optioneel thumbnail-icoon rechtsboven in embed (128x128 of 256x256)

yaml
Copy code

---

## 🔗 Gebruik in `keys.cfg`

Voorbeeld hoe je deze links kunt opnemen in je `keys.dev`, `keys.test`, of `keys.live`:

```cfg
set logs_logo "https://raw.githubusercontent.com/<user>/deadwoodridge-branding/main/branding/dwr_logo.png"          # Author icon
set logs_footer_logo "https://raw.githubusercontent.com/<user>/deadwoodridge-branding/main/branding/dwr_footer.png" # Footer icoon
set logs_avatar "https://raw.githubusercontent.com/<user>/deadwoodridge-branding/main/branding/dwr_avatar.png"      # Webhook avatar
#set logs_image "https://raw.githubusercontent.com/<user>/deadwoodridge-branding/main/branding/dwr_banner.png"      # Optionele banner
#set logs_thumbnail "https://raw.githubusercontent.com/<user>/deadwoodridge-branding/main/branding/dwr_thumb.png"   # Optionele thumbnail
🎨 Aanbevolen afmetingen
Logo (author): 256x256 of 512x512

Footer icoon: 32x32 of 64x64

Avatar: 128x128 of 256x256

Thumbnail: 128x128 of 256x256

Banner: 800x200 (tot 1200x400)

ℹ️ Info
Afbeeldingen worden publiek geladen via de Raw links van deze repo.

Discord cachet afbeeldingen; wijzig de bestandsnaam als je een nieuw logo uploadt.

Houd bestanden klein (PNG/JPG), max. ~1 MB per stuk.

yaml
Copy code

---

👉 Wil je dat ik ook meteen een voorbeeld Discord **embed screenshot** voor je schets, zodat je direct ziet waar logo, avatar, footer en banner terechtkomen?