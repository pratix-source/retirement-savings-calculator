# Pratix Retirement Savings Calculator v2 Rebuilt Stable

Tarayıcıda çalışan emeklilik birikimi hesaplayıcısıdır. Ana uygulama `tools/retirement-savings-calculator.html` dosyasındadır ve build adımı gerektirmez.

## Vercel yayınlama

Bu paket özellikle **düz proje kökü** olarak hazırlanmıştır. ZIP’i açtığınızda `index.html`, `vercel.json`, `tools/`, `locales/` ve `data/` doğrudan açılan klasörün içinde bulunmalıdır. Bu dosyaları ikinci bir üst klasörün içine taşımayın.

GitHub repository kökünde `index.html` görünmelidir. Vercel Project Settings içinde **Root Directory** olarak `.` seçili olmalı; Framework Preset **Other**, Build Command boş ve Output Directory boş bırakılmalıdır. Eğer GitHub repository içinde bu uygulama bir alt klasörde bulunuyorsa Root Directory’yi `index.html` dosyasının bulunduğu alt klasöre ayarlayın.

Kök URL için `index.html`, `/` ve `/tools` adresleri için `vercel.json` hazır durumdadır.
