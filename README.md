# NFC Scanner
NFC Tags are small chips which you can get in the form of stickers, cards, rings or even keychain. They can store a small amount of data in the range of hundreds of bytes. These are passive things which can work without a power supply or rely on other devices for power such as an NFC Tag depends on your Phone or the NFC readers to work.

# What is CoreNFC?

“Using Core NFC, you can read Near Field Communication (NFC) tags of types 1 through 5 that contain data in the NFC Data Exchange Format (NDEF). To read a tag, your app creates an NFC NDEF reader session and provides a delegate. A running reader session polls for NFC tags and calls the delegate when it finds tags that contain NDEF messages, passing the messages to the delegate. The delegate can read the messages and handle conditions that can cause a session to become invalid.”
- Apple’s official documentation on CoreNFC.

# What is NDEF ?

NDEF (NFC Data Exchange Format) is a protocol provided by the NFC Forum which is used to describe how a NFC tag must expose data. Every NDEF record is made up by two components:
A record type (check out this doc)
Payload data
Once a device (i.e. an iPhone or an Apple Watch) is ready to read data from a NFC tag and it’s placed near the tag, these components are exchanged between the NFC tag and the reader.
CoreNFC is able to interact with NFC tags 1/2/3/4 and 5.
