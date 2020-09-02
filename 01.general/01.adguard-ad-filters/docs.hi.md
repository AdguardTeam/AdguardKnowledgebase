---
title: 'AdGuard एड फिल्टर्स'
taxonomy:
    category:
        - docs
visible: true
---

* [इंट्रोडक्शन](#introduction)
* [फिल्टर्स पॉलिसी](#policy)
* [AdGuard फिटर में कंट्रीब्यूट्स करें](#contribute)
* [AdGuard फिल्टर्स](#filters)


<a name="introduction"></a>
## इंट्रोडक्शन

यह आर्टिकल उन फ़िल्टर के बारे में है जो AdGuard में इस्तेमाल होते हैं और अलग ऐड ब्लॉकिंग सॉफ्टवेयर्स में (उदाहरण uBlock Origin)। हर एक फ़िल्टर एक रूल को रिप्रेजेंट करता है, जो AdGuard मैं इस्तेमाल होते हैं और अलग प्रोग्राम्स में जो प्राइवेसी को खतरे में डालते हैं (उदाहरण बैनर्स, पाप-अप्स, ट्रैकर्स, इत्यादि)। रूल्स एक पर्टिकुलर इंटरनेट सेगमेंट के लिए (जर्मन फिल्टर, रशियन प्रिंटर), एक स्पेसिफिक काम के लिए (सोशल मीडिया फिल्टर, ट्रैकिंग प्रोटेक्शन फिल्टर, इत्यादि) इन सब को एक लिस्ट में दाल सकतें हैं  - फिल्टर - इसको बंद/चालू किया जा सकता है।

<a name="policy"></a>
## AdGuard फिल्टर्स पॉलिसी

हमारी प्राइवेसी पॉलिसी [यहां पर मौजूद है](https://kb.adguard.com/general/adguard-filter-policy)।

<a name="contribute"></a>
## AdGuard फिल्टर में कैसे कंट्रीब्यूशन करें

हम बहुत ही खुश किस्मत हैं कि हमारे पास एक ऐसी कम्युनिटी है जो सिर्फ AdGuard को प्यार ही नहीं करती, पर वापस में कुछ देना भी चाहती है। बहुत सारे लोग वालंटियर करके अलग-अलग यूजर्स के एक्सपीरियंस को AdGuard पर अच्छा बनाना चाहती है, हम तो सिर्फ खुशी हो सकते हैं जो मेंबर सबसे ज्यादा एक्टिव रहते हैं कम्युनिटी में, तोह आप क्या कर सकते हैं? 

### रिपोर्ट इश्यूज

हम कम्युनिटी पर निर्भर करते हैं हमारी फिल्टर्स के समस्याओं के बारे में मालूम कराने के लिए। इस तरह हम सबसे ज्यादा एफिशिएंट हो सकते हैं हमारे टाइम के साथ और हम हमारे फिल्टर को हमेशा अपडेट कर कर रख सकते हैं। रिपोर्ट को सबमिट करने के लिए, कृपया इसे इस्तेमाल करें [वेब रिर्पोटिंग टूल](https://agrd.io/report)। 

### फिल्टर रूस को सजेस्ट करना

आप बहुत सारे इशू पा सकतें हैं हमारी [GitHub  फिल्टर रेपोसिटरी](https://github.com/AdguardTeam/AdguardFilters/issues) पर। हर एक वेबसाइट एक इशू को रेफरेंस करते हुए — मिस किया हुआ ऐड, फॉल्स पॉजिटिव, इत्यादि — कोई भी एक चुने और अपने रूल्स की सजेशंस को कमेंट में डालें। AdGuard इंजीनियर उन सजेशंस को रिव्यू करेंगे, और अगर वह सही निकले तो उन रुल्स को AdGuard फिल्टर्स में डाला जाएगा।


यहां हमारी [ऑफिशियल डॉक्यूमेंटेशन](https://kb.adguard.com/general/how-to-create-your-own-ad-filters) है AdGuard फिल्टरिंग रूल्स सिंटेक्स पर। आपको उन्हें पढ़ना होगा कोई भी रोल बनाने से पहले।

### कंट्रीब्यूट करने के लिए दूसरे तरीके

यहां हमारे [इस खास पेज पर](https://adguard.com/contribute.html) मिलेंगे और भी कंट्रीब्यूट्स करने के तरीके जो लोग उनमें इच्चित हैं।

<a name="filters"></a>
## AdGuard फिल्टर्स

* **बेस फिल्टर** — इंग्लिश कंटेंट से एड्स को निकालता है। ओरिजनली बेस्ड [EasyList](https://easylist.to/) फ़िल्टर पर, हमारी तरफ से बदला गया हुआ। [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/2.txt)
* **ट्रैकिंग प्रोटेक्शन फिल्टर** — एक अच्छी खासी अलग-अलग काउंटर और वेब एनालिटिक्स की लिस्ट है। इस्तेमाल करें अपनी ऑनलाइन एक्टिविटी को छिपाने के लिए और ना ट्रक होने के लिए [रुल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/3.txt)
* **सोशल मीडिया फिल्टर** — पॉपुलर वेबसाइट से "लाइक" और "ट्वीट" बटन निकालता है, और अलग-अलग सोशल मीडिया इंटीग्रेशन को भी। [रुक्स
को देखें](https://filters.adtidy.org/extension/chromium/filters/4.txt)
* **अन्नायंसेस फिल्टर** —  वेबपेज पर से परेशान करने वाली चीजों को निकालता है, कुकी नोटिस को, थर्ड-पार्टी विजिट को और पेज के अंदर के पापा-अप को (सोशल मीडिया एलिमेंट्स के अलावा)। Fanboy Annoyances लिस्ट से प्रेरित, पर उसकी नकल नहीं करता. [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/14.txt)
* **सर्च एड और सेल्फ-प्रमोशन अनब्लॉक करने का फिल्टर** — उन एड्स को अनलॉक करता है। जो यूजर्स के लिए उपयोगी हो सकते हैं। इस बारे में और जानने के लिए [इस पेज](https://kb.adguard.com/en/general/search-ads-and-self-promotion) पर जाएं। [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/10.txt)
* **रशियन फिल्टर** — रशियन वेबसाइट से एड्स को निकालता है। पहले बेस्ड [RU AdList](https://code.google.com/p/ruadlist/) फिल्टर पर और बाद में हमसे कंपलीटली इंडिपेंडेंटली डिवेलप किया हुआ। फिलहाल RU AdList left से ज्यादा इंटरसेक्शन नहीं होता। [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/1.txt)
* **जर्मन फिल्टर** — जर्मन वेबसाइट से एड्स को निकालता है। ओरिजनली बेस्ड [EasyList Germany](https://easylist.to/) फिल्टर पर, बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से. [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/6.txt)
* **फ्रेंच फिल्टर** — फ्रेंच वेबसाइट से एड्स को निकालता है। ओरिजनली [Liste FR](https://forums.lanik.us/viewforum.php?f=91) फिल्टर पर बेस्ड बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से. [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/16.txt)
* **जापानीस फिल्टर** —जापानीस वेबसाइट से एड्स को निकालता है। ओरिजनली [Fanboy’s Japanese](https://www.fanboy.co.nz/fanboy-japanese.txt) फिटर पर बेस्ड बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से. [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/7.txt)
* **डच बिल्डर** — डच वेबसाइट से एड्स कोलकाता है। ओरिजनली  [EasyList Dutch](https://easylist.to/) फिल्टर पर बेस्ड बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से. [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/8.txt)
* **स्पेनिश/पॉर्चुगीस फिल्टर** — एड्स को निकालता है स्पेनिश/पॉर्चुगीस वेबसाइट मैं से। ओरिजनली [Fanboy’s Spanish/Portuguese](https://www.fanboy.co.nz/fanboy-espanol.txt) फिल्टर पर बेस्ड बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से। [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/9.txt)
* **टर्किश फिल्टर** — टर्किश वेबसाइट से एड्स निकालता है। इसे हमने बनाया है यूजर कंप्लेंट के हिसाब से [रुल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/13.txt)
* **चाइनीस फिल्टर** — चाइनीस एड्स को निकालता है। ओरिजनली [EasyList China](http://abpchina.org/forum/forum.php) फिल्टर बेस्ड बाद में हमसे मॉडिफाई किया हुआ यूजर कंप्लेंट के हिसाब से। [रूल्स को देखें](https://filters.adtidy.org/extension/chromium/filters/224.txt)
* **एक्सपेरिमेंटल फिल्टर** — उनको फ़िल्टर के लिए है जो अभी भी टेस्टिंग में है और दूसरे वेबसाइट के साथ टक्कर पैदा कर सकते हैं। अगर रूल्स कोई कोई भी समस्या के बिना काम करते हैं तो उन्हें फिल्टर्स लिस्ट में डाला जाता है। [रूल्स देखें](https://filters.adtidy.org/extension/chromium/filters/5.txt)
* **मोबाइल एड्स फोल्डर** — मोबाइल पर सारे जो जानने में है उन एड नेटवर्क्स से दिखने वाली एडवरटाइजिंग को बंद करता है [रुल्स देखें](https://filters.adtidy.org/extension/chromium/filters/11.txt)
* **DNS फिल्टर** — अलग-अलग फिल्टर से बना हुआ (AdGuard बेस फिल्टर, सोशल मीडिया फिल्टर, स्पाइडर फिल्टर, मोबाइल एड्स फिल्टर, EasyList और EAsyPrivacy) और सुलझाया हुआ और कंपैटिबल है हमारे DNS ब्लॉकिंग से। यह फिल्टर को AdGuard DNS सर्विस यूज करते हैं ब्लॉकिंग और ट्रैकिंग रुकने के लिए। DNS-लेवल ब्लॉकिंग के बारे में ज्यादा जानने के लिए, जाएं [इस पेज पर](https://adguard.com/adguard-dns/overview.html)। [रूल्स देखें](https://adguardteam.github.io/AdGuardSDNSFilter/Filters/filter.txt)