# Flash Notes

By: Russel Zhang, Calvin Dong, Nick Makharimets, and William Tran
Created during Hack The North 2019

Summary
-----------
Web app that takes uses language processing, including Microsoft Azure Text Analytics and Google Cloud Natural Language API, to automatically generate flashcards based on typed notes.

Features:
-----------
- Microsoft Azure Text Analytics to finds keywords in the text
- Google Cloud Natural Language API disciphers different parts of speech 
- Our own algorithms take the output of the APIs and determine if given strings are valid phrases that would make sense to users
- Phrases are outputted to flash cards on a user-friendly website
