# cameraToText
An easy Swift class to take photos and send them as a text. 

Implementation is simple: 
Just copy the class into your project, initialize the class, run the setData function, and present it. Here's a code example: 
```
let ct = cameraToText.init()
ct.setData(txt: "someMessageText", rec: ["123456789","234567890"], subj: "someSubject") 
ct.modalPresentationStyle = .overFullScreen
present(ct, animated: true)
ct.initCameraToText() 
```
Cheers! 
