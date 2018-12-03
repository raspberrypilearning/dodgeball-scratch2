--- challenge ---
## चुनौती: गुरुत्वाकर्षण में सुधार
आपकी गेम में एक अन्य त्रुटि है: अगर _कोई_ भाग नीले प्लेटफॉर्म को छूता है, तो गुरुत्वाकर्षण आपके कैरेक्टर को नीचे की ओर नहीं खींचेगा – यहाँ तक कि इसके सिर को भी नहीं! आप सीढ़ी के शीर्ष तक चढ़कर और फिर बाएँ गति करके इसका परीक्षण कर सकते हैं।

![screenshot](images/dodge-gravity-bug.png)

क्या आप इस त्रुटि को दूर कर सकते हैं? ऐसा करने के लिए, आपको अपने कैरेक्टर को भिन्न रंग की पतलून (_सभी_ पोशाकों पर) देनी होंगी...

![screenshot](images/dodge-trousers.png)

...और फिर कोड को बदल दें: 

```blocks
	< [#0000FF] रंग को छू रहा है? >
```

with:

```blocks
	< अगर [#00FF00] रंग [#0000FF] को छू रहा है? >
```

यह सुनिश्चित करने के लिए अपने सुधारों का परीक्षण करना याद रखें कि आपने त्रुटि को दूर कर लिया है!




--- /challenge ---