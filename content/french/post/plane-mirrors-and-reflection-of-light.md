---
title: "समतल दर्पण और प्रकाश के परावर्तन की अवधारणा"
date: 2022-03-30T15:40:24+06:00
# post thumb
images:
  - "images/post/optics/reflection-of-light.jpeg"
#author
author: "Mayank Sharma"
# description
description: ""
# Taxonomies
categories: ["optics"]
tags: ["reflection-of-light","plane-mirror"]
type: "trending" # available type (epic, trending, popular, or regular)
draft: false
# Maths
katex: true
---

इस लेख में, हम आपको प्रकाश के कुछ बहुत ही बुनियादी गुणों से परिचित कराएंगे और समतल दर्पण की अवधारणा पर कुछ प्रकाश डालेंगे।

<div class="toc-mak">
<img src="../../../images/pencil.png">
<b>Table of Contents</b>
<ul>
<li>प्रकाश क्या होता है?</li>
<li>प्रकाश अंतरिक्ष और पदार्थ में कैसे यात्रा करता है?</li>
<li>प्रकाश का परावर्तन क्या होता है?</li>
<li>दर्पण क्या होता है?</li>
<li>समतल दर्पण द्वारा बनने वाले प्रतिबिम्ब के अभिलक्षण</li>
<li>समतल दर्पणों के उपयोग</li>
</ul>
</div>

## प्रकाश क्या होता है?

प्रकाश (या दृश्य प्रकाश) विद्युत चुम्बकीय वर्णक्रम का एक छोटा सा खंड है जिसे मानव आंखों द्वारा पहचाना जा सकता है।

विद्युत चुम्बकीय तरंगों में आवृत्तियों और तरंग दैर्ध्य की एक विस्तृत श्रृंखला होती है। लेकिन हमारी रेटिना बहुत बड़ी तरंग दैर्ध्य (जैसे इन्फ्रारेड) या बहुत छोटी तरंग दैर्ध्य (जैसे एक्स-रे) वाली विद्युत चुम्बकीय तरंगों का पता नहीं लगा सकती है। हम केवल उन विद्युत चुम्बकीय तरंगों का पता लगा सकते हैं जिनकी तरंग दैर्ध्य लगभग 400 nm से 750 nm तक होती है। इसे हम आम शब्दों में "प्रकाश (light)" कहते हैं।

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>प्रकाशिकी (Optics)</b><br>

प्रकाशिकी भौतिकी की वह शाखा है जिसमें हम प्रकाश के व्यवहार और गुणों का अध्ययन करते हैं। यहां हम अध्ययन करते हैं कि प्रकाश अपने आस-पास के पदार्थ के साथ कैसे व्यवहार करता है, और वह विभिन्न उपकरण जो हम उसका पता लगाने और अध्ययन करने के लिए प्रयोग करते हैं।
</div>

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>प्रकाश की दोहरी प्रकृति</b><br>

हम पहले से ही जानते हैं कि प्रकाश मूल रूप से एक विद्युत चुम्बकीय तरंग है। हालांकि अन्य क्वांटम स्तर की घटनाओं की तरह, इसमें कण गुण भी होते हैं। प्रकाश के कण को ***फोटोन (photon)*** कहते हैं।

हालांकि, हम विद्युत चुम्बकीय तरंगों की दोहरी प्रकृति पर एक अलग लेख में ध्यान केंद्रित करेंगे।
</div>


## प्रकाश अंतरिक्ष और पदार्थ में कैसे यात्रा करता है?

प्रकाश सदैव एक सीधी रेखा में गमन करता है। इसे साबित करना काफी आसान है। यदि आपके पास एक लेज़र या टॉर्च है, तो आप उसके सामने एक अपारदर्शी वस्तु रख सकते हैं और देख सकते हैं कि यह प्रकाश किरण को आगे बढ़ने से रोक देता है। हमें उस वस्तु की छाया उसके पीछे के पर्दे पर मिलती है।
<img src="../../../images/post/optics/reflection-of-light2.jpeg" alt="Reflection of Light" style="width:99%;height:99%;"> <br>

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>ग्रहण, प्रकाश के सीधी रेखा में गमन के कारण होते हैं</b><br>

यही सूर्य और चंद्र ग्रहण के पीछे का कारण है।

* ***सूर्य ग्रहण***: जब चंद्रमा, सूर्य और पृथ्वी के बीच आ जाता है, तो सूर्य का प्रकाश पृथ्वी की सतह तक नहीं पहुंच पाता है। सूर्य, पृथ्वी से अदृश्य हो जाता है और हम चंद्रमा की छाया में आ जाते हैं। अतः चन्द्रमा यहाँ अपारदर्शी वस्तु के रूप में कार्य करता है।

* ***चंद्र ग्रहण***: जब पृथ्वी, सूर्य और चंद्रमा के बीच आ जाती है, तो सूर्य का प्रकाश चंद्रमा की सतह तक नहीं पहुंच पाता है। चन्द्रमा से सूर्य अदृश्य हो जाता है और वह पृथ्वी की छाया में आ जाता है। इसलिए हम चंद्र ग्रहण के दौरान चंद्रमा को नहीं देख पाते हैं (हमारी पृथ्वी की छाया इसे रात के आकाश में छुपा लेती है)। तो, यहाँ पृथ्वी अपारदर्शी वस्तु के रूप में कार्य करती है।

हमें ये विभिन्न प्रकार के ग्रहण सिर्फ इसलिए देखने को मिलते हैं क्योंकि प्रकाश किसी भी माध्यम में एक सीधी रेखा में यात्रा करता है।
</div>

हमें किस प्रकार की छाया मिलेगी, यह उस प्रकाश स्रोत पर निर्भर करेगा जिसका हम उपयोग कर रहे हैं।

* यदि हम प्रकाश के बिंदु स्रोत का उपयोग कर रहे हैं, जैसे कि एक लेज़र बीम, तो बनने वाली छाया पूर्ण अंधकार का क्षेत्र होगी। इस क्षेत्र को अम्ब्रा (umbra) कहा जाता है।
<img src="../../../images/post/optics/reflection-of-light3.png" alt="Reflection of Light" style="width:99%;height:99%;"> <br>

* यदि हम प्रकाश के विस्तारित स्रोत का उपयोग कर रहे हैं, जैसे कि एक मशाल, तो बनने वाली छाया के दो क्षेत्र होंगे। मध्य गर्भ क्षेत्र (umbra) पूर्ण अंधकार का क्षेत्र होगा। लेकिन यह आंशिक अंधेरे के क्षेत्र से भी घिरा होगा, जिसे पेनम्ब्रा (penumbra) कहा जाता है।

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>नोट</b><br>

ध्वनि तरंगों के विपरीत जो कोनों पर मुड़ सकती हैं और फिर भी आगे जा सकती हैं, प्रकाश तरंगें हमेशा सीधी रेखाओं में यात्रा करती हैं। इसलिए हम आस-पास के कमरों से लोगों की आवाजें सुन सकते हैं, भले ही हम उन्हें देख न सकें।
</div>


## प्रकाश का परावर्तन क्या होता है?

हालांकि प्रकाश हमेशा सीधी रेखा में चलता है, लेकिन यह मुड़ सकता है और सतहों से परावर्तित हो सकता है। उदाहरण के लिए, कांच के माध्यम (जैसे एक प्रिज्म) में प्रवेश करने पर प्रकाश अपने मूल पथ से विक्षेपित हो जाता है। इसे अपवर्तन (refraction) कहते हैं। यह अंतरिक्ष में भारी पिंडों के पास से गुजरते हुए भी मुड़ जाता है (जैसे हमारे सूर्य के पास से गुजरते हुए), अंतरिक्ष-समय (space-time) में गुरुत्वाकर्षण द्वारा उत्त्पन्न की गयी वक्रता (curvature) के कारण (यह आइंस्टीन/Einstein द्वारा सुझाया गया था)।

प्रकाश से संबंधित कई अन्य घटनाएं हैं, उदा. यह आकाश में उपस्थित छोटे कणों पर टकराकर बिखर जाता है, यह प्रिज्म या ऐसे अन्य माध्यम में प्रवेश करने पर अपने घटकों में विभाजित हो जाता है (इंद्रधनुष इसी घटना के कारण बनता है), आदि।

हालाँकि, यहाँ हमारा ध्यान प्रकाश के परावर्तन (Reflection of Light) की परिघटना पर होगा। आइए इसे विस्तार से समझते हैं।

***प्रकाश का परावर्तन***: जब प्रकाश की किरण किसी सतह पर गिरती है और उसी माध्यम में वापस फेंकी जाती है, तो इस घटना को प्रकाश का परावर्तन कहा जाता है।

इसे नीचे दिए गए चित्र में दर्शाया गया है:
<img src="../../../images/post/optics/reflection-of-light1.png" alt="Reflection of Light" style="width:99%;height:99%;"> <br>
 
उपरोक्त आकृति में, एक समतल दर्पण प्रकाश को परावर्तित करने वाली सतह के रूप में कार्य कर रहा है।

### परावर्तन के नियम

अब, आइए प्रकाश के परावर्तन की परिघटना से संबंधित कुछ शब्दावली और नियमों को देखें।
* आने वाली प्रकाश पुंज को अक्सर ***आपतित किरण (Incident ray)*** कहा जाता है और जावक प्रकाश पुंज को अक्सर ***परावर्तित किरण (Reflected ray)*** कहा जाता है। आपतन बिंदु (point of incidence) से होकर परावर्तक सतह के लंबवत खींची गई आभासी रेखा को ***अभिलंब रेखा (Normal)*** कहा जाता है।
* आपतित किरण, परावर्तित किरण और अभिलंब सभी एक ही तल पर होते हैं।
* आपतन कोण (∠i) = परावर्तन कोण (∠r)

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>नोट</b><br>

किसी वस्तु का रंग उसके द्वारा परावर्तित दृश्य प्रकाश के प्रकार पर निर्भर करता है। उदाहरण के लिए, पौधे हरे दिखते हैं क्योंकि वे हरे प्रकाश को परावर्तित करते हैं। रक्त लाल दिखता है, क्योंकि यह लाल प्रकाश को परावर्तित करता है।
</div>


## दर्पण क्या होता है?

जब प्रतिबिंब या परावर्तन की बात आती है, तो हम अक्सर दर्पण का उपयोग करते हैं। अर्थात्, आप अक्सर दर्पण को प्रकाश पुंज को परावर्तित करने वाली सतह के रूप में कार्य करते हुए पाएंगे।

जैसा कि हम में से अधिकांश पहले से ही जानते हैं, दर्पण मूल रूप से एक कांच की सतह होती है जिसका एक चेहरा पॉलिश किया हुआ होता है।

* समतल शीशे की सतह को समतल दर्पण (Plane Mirror) कहते हैं।
* शीशे की घुमावदार सतह को गोलाकार दर्पण (Spherical Mirror) कहा जाता है।


### समतल दर्पण क्या होता है?

समतल दर्पण (Plane Mirror) एक समतल कांच की सतह होता है, जिसका एक फलक पॉलिश किया हुआ होता है।


## समतल दर्पण द्वारा बनने वाले प्रतिबिम्ब के अभिलक्षण

### छवि दूरी, आकार और प्रकृति से संबंधित विशेषताएं

* समतल दर्पण से किसी वस्तु की दूरी, समतल दर्पण से उसके प्रतिबिम्ब की दूरी के बराबर होती है। अतः, यदि कोई वस्तु दर्पण के सामने d इकाई दूर है, तो उसका प्रतिबिंब दर्पण के पीछे d इकाई दूर होगा। वस्तु को उसके प्रतिबिम्ब से मिलाने वाली रेखा समतल दर्पण के अभिलम्ब होती है।

* समतल दर्पणों के मामले में, प्रतिबिम्ब का आकार = वस्तु का आकार
<img src="../../../images/post/optics/reflection-of-light4.svg" alt="Reflection of Light" style="width:99%;height:99%;"> <br>

* समतल दर्पण द्वारा बनाई गई छवि होती है: आभासी (Virtual), सीधी (Erect), और पार्श्व रूप से उल्टी (वस्तु का दाहिना भाग छवि के बाईं ओर दिखाई देता है)

<div class="toc-mak">
  <img src="../../../images/pencil.png">
  <b>नोट</b><br>

किसी वस्तु का पूर्ण आकार का प्रतिबिम्ब बनाने के लिए, समतल दर्पण का आकार वस्तु के रैखिक आकार का कम से कम आधा होना चाहिए।
</div>


### दर्पण या वस्तु की गति से संबंधित विशेषताएं

* यदि समतल दर्पण को θ डिग्री घुमाया जाता है, तो परावर्तित किरण उस कोण के दोगुने, अर्थात 2θ डिग्री से घूमेगी।
* यदि कोई वस्तु, दर्पण की ओर v इकाई/सेकंड की गति से चलती है, तो उसका प्रतिबिम्ब वस्तु की ओर इस गति से दुगनी गति से, अर्थात् 2v इकाई/सेकंड से गति करता हुआ प्रतीत होता है।


### अनेक दर्पणों से संबंधित विशेषताएं

* यदि दो समतल दर्पणों को एक दूसरे के समानांतर रखा जाए, तो अनंत संख्या में प्रतिबिंब बनते हैं।
* <p> हालांकि, यदि दो समतल दर्पण समानांतर नहीं हैं, तो बनने वाले प्रतिबिम्बों की संख्या परिमित होती है। θ कोण पर झुके हुए दो समतल दर्पणों के बीच स्थित किसी वस्तु की छवियों की संख्या, n = \(\frac{360°}{θ} - 1\) </p>


## समतल दर्पणों के उपयोग

समतल दर्पण सबसे व्यापक रूप से उपयोग किए जाने वाले दर्पणों में से एक है। आइए, इसके कुछ उपयोगों को सूचीबद्ध करें।
* इसका उपयोग शीशे की तरह खुद को देखने में किया जाता है।
* इसका उपयोग बहुरूपदर्शक (kaleidoscope), परिदर्शी / पेरिस्कोप (periscope), आदि में किया जाता है।
