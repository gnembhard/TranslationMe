# Project 6 - TranslationMe

Submitted by: **Giovanni Nembhard Z23567778**

**TranslationMe** is an iOS app built with SwiftUI that allows users to translate words, phrases, or sentences between multiple languages. The app leverages a translation API to perform real-time translations and uses Firebase Firestore to store translation history. Users can view their previous translations and clear them at any time. The app also features a clean, card-style UI with language selection and modern buttons to improve usability.

Time spent: **5 hours** spent in total

---

## Required Features

The following **required** functionality is completed:

- [x] Users open the app to a TranslationMe home page with a place to enter a word, phrase or sentence, a button to translate, and another field that should initially be empty  
- [x] When users tap translate, the word written in the upper field translates in the lower field. The requirement is only that you can translate from one language to another.  
- [x] A history of translations can be stored (in a scroll view in the same screen)  
- [x] The history of translations can be erased  
## Stretch Features
The following **stretch** features are implemented:

- [x] Add a variety of choices for the languages (English, Spanish, French, German, Italian, Portuguese, Chinese)  
- [x] Add UI flair (card-style input/output sections, rounded buttons, shadows, accent colors, footer with creator name)  



---

## Video Walkthrough

Here's a walkthrough:

---

## Notes

Challenges encountered while building the app:

- **Partial translations from MyMemory API**: Sometimes returned translations had leftover English text or `%` markers. This was cleaned client-side, but switching to an alternative API like LibreTranslate could improve accuracy.  

---

## License

