WorldTime Pro

Currency Rates update:
- Added a Currency Rates page with USD, INR, EUR, GBP, AED, JPY, CAD, AUD and SGD.
- Added a currency converter and manual/automatic rate refresh.
- Uses the free ExchangeRate-API open access endpoint (no API key required).
- Rates are reference rates updated periodically, not tick-by-tick live Forex quotes. Internet access is required to fetch new rates; the most recently loaded rates are cached in the browser.

Open index.html from a web server or deploy the folder to your static website host. The existing WorldTime Pro features remain included.


## मोबाईलमध्ये App म्हणून वापरणे (PWA)

1. ही संपूर्ण `worldtime-pro-main` फोल्डर HTTPS असलेल्या वेब होस्टिंगवर अपलोड करा.
2. अपलोड केलेली वेबसाइट Android Chrome किंवा iPhone Safari मध्ये उघडा.
3. Android: Chrome मधील ⋮ मेनू → **Install app** किंवा **Add to Home screen** निवडा.
4. iPhone: Safari मधील Share बटण → **Add to Home Screen** निवडा.
5. Home Screen वरील WorldTime Pro आयकॉनवर टॅप करून App सुरू करा.

टीप: ZIP फाईल थेट उघडून PWA install करता येत नाही. PWA install आणि Service Worker साठी वेबसाइट HTTPS वर प्रकाशित असणे आवश्यक आहे (localhost वगळता).


## WorldTime Pro Premium Dark + Orange Update
- Default app appearance is now Premium Dark + Orange.
- Android install prompt is shown when Chrome offers PWA installation.
- Updated PWA theme/background colors and service-worker cache version.
- Existing dashboard, clocks, map, time converter, currency rates, alarms and settings are preserved.
- Publish the complete folder to HTTPS hosting before installing on Android.
