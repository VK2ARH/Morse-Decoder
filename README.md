# Morse-Decoder
VK2ARH implementation of Jon Dawson's 'Hamfist' Morse Decoder using a Raspberry Pi Pico.
<img width="1396" height="839" alt="image" src="https://github.com/user-attachments/assets/7bda8d7e-1eb6-445c-9885-a2767ce00306" />
This repository holds the files and documentation to support my Morse Decoder Project, which is an implementation of Jon Daswson's Hamfist decoder using a 'PCB Sandwich' type of construction supporting the use of through hole devices. 
<img width="1299" height="1148" alt="image" src="https://github.com/user-attachments/assets/f66bc269-7153-4035-93f1-3fc5ae692b81" />
The project support touch screen interfaces as well as any future implementation which makes use of the TFT's SD card reader. Legacy support for the use of four push buttons to support operation of the decoder are also included.
<img width="1580" height="1036" alt="image" src="https://github.com/user-attachments/assets/fb2eef9a-32a2-48c8-bd44-a67e0ea1cec6" />
<img width="1494" height="1118" alt="image" src="https://github.com/user-attachments/assets/9602e863-d668-4169-9660-47707421f9c3" />

In addition to Jon's base design, this project has added an audio monitoring circuit with volume control, which enables you to hear an incomming signal from your receiver via an external speaker or earphone, after you have plugged in the Morse Decoder to the receivers headphone socket which normally results in loss of audio from the receiver. The Morse Decoder also includes a PTT circuit which will ground the 'ring' connection of the Tx audio line when using the decoder to Tx CW. This feature enables 'keying' the PTT circuit of any external CW transmitter.

Full details of the design brief and capability of the decoder together with links to the latest software can be found at Jon Web site : https://101-things.readthedocs.io/en/latest/ham_fist.html 
