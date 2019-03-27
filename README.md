# nfcscanner
NFC Tags are small chips which you can get in the form of stickers, cards, rings or even keychain. They can store a small amount of data in the range of hundreds of bytes. These are passive things which can work without a power supply or rely on other devices for power such as an NFC Tag depends on your Phone or the NFC readers to work.

What is CoreNFC?

“Using Core NFC, you can read Near Field Communication (NFC) tags of types 1 through 5 that contain data in the NFC Data Exchange Format (NDEF). To read a tag, your app creates an NFC NDEF reader session and provides a delegate. A running reader session polls for NFC tags and calls the delegate when it finds tags that contain NDEF messages, passing the messages to the delegate. The delegate can read the messages and handle conditions that can cause a session to become invalid.”
- Apple’s official documentation on CoreNFC.
