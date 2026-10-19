# Aavelyra पर नए Products और असली Photos कैसे जोड़ें (Hindi)

यह guide केवल **Aavelyra** वेबसाइट के लिए है। Rankers Nest repository को न खोलें और न बदलें।

## सबसे आसान तरीका: मोबाइल से

1. यह repository खोलें: https://github.com/vashishthamadhusudan-stack/aavelyra
2. GitHub में अपने account से sign in करें।
3. पहले product की असली फोटो तैयार करें। अच्छी रोशनी में सामने की फोटो लें; चाहें तो back, fabric close-up और size label की फोटो भी रखें।
4. फोटो का नाम छोटा और साफ रखें, जैसे `cotton-kurti-maroon-01.jpg`।
5. Repository में `assets/products` folder खोलें। अगर folder अभी मौजूद नहीं है, तो `assets/products/README.md` फ़ाइल बनाकर पहले folder बनाएँ।
6. `Add file` → `Upload files` चुनें, फोटो चुनें और `Commit changes` दबाएँ।
7. अब `index.html` खोलें और pencil/Edit आइकन दबाएँ।
8. जिस product card को बदलना है, उसके image URL को अपनी uploaded image के GitHub Pages URL से बदलें। उदाहरण:
   `https://vashishthamadhusudan-stack.github.io/aavelyra/assets/products/cotton-kurti-maroon-01.jpg`
9. उसी product card में नाम, कीमत, category और विवरण भी ठीक करें। फिर `Commit changes` करें।
10. कुछ मिनट बाद वेबसाइट refresh करें। कभी-कभी मोबाइल browser cache के कारण पुरानी तस्वीर दिखती है; ऐसे में hard refresh या private tab में खोलें।

## हर Product के लिए यह जानकारी पहले लिख लें

- Product name / SKU: उदाहरण AV-KU-001
- Category: Kurtis / Kurti Sets / Dresses / Tops / Co-ord Sets
- Supplier-confirmed selling price: ₹____
- Fabric: ____
- Available sizes: ____
- Actual stock / supplier availability: ____
- Delivery charge and dispatch time: ____
- Photo usage permission from supplier: Yes / No
- Return / exchange policy: ____

## जरूरी बातें

- Supplier की फोटो वेबसाइट पर तभी इस्तेमाल करें जब उसने इस्तेमाल की अनुमति दी हो।
- फोटो और stock की पुष्टि के बिना product को “In Stock” न दिखाएँ और order की गारंटी न दें।
- वेबसाइट की कीमत supplier से पुष्टि की हुई हो; अनुमानित कीमत को वास्तविक कीमत की तरह न दिखाएँ।
- पहले एक product पर प्रक्रिया आज़माएँ, फिर बाकी products जोड़ें।
- बदलाव करने से पहले `index.html` की मौजूदा copy सुरक्षित रख लें।
- यह वेबसाइट static GitHub Pages site है; product जोड़ने के लिए कोई अलग admin dashboard अभी उपलब्ध नहीं है। GitHub में file edit करके ही बदलाव publish होंगे।
