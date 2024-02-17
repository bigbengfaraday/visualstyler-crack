#Unlimited License for .NET Projects with VisualStyler library

1. Create .NET Project and add VisualStyler Object.
2. Open `<form>.Designer.vb`
3. Change:
   ```vb
   Me.VisualStyler2.License = CType(resources.GetObject("VisualStyler2.License"), SkinSoft.VisualStyler.Licensing.VisualStylerLicense)
   ```
   To:
   ```vb
Dim lic As SkinSoft.VisualStyler.Licensing.VisualStylerLicense = New VisualStylerLicense
 lic.SavedKey = "XdJAN1zS32BWp/M4YW/Yxo4HJJBhgsigWDVHiTdGCKOlrhAWCxJeboDwPz1P7DiPL8KEIvefgEEawUcE6hwOCKVh5uefjo1qT05YGEiob0z5Y1jQPmsjdZjE3WeQDRVzhWHUlItIuojpQeIc6q981hAjzNqEVG2t"
 Me.VisualStyler2.License = CType(lic, SkinSoft.VisualStyler.Licensing.VisualStylerLicense)`
```
 Done!
