# IpaSpeak Source
To download the source code of IpaSpeak click on the release tab.

/Intro

IpaSpeak is composed of two components: 

-The back- end is the espeak vocal synthesizer (http://espeak.sourceforge.net/) which generates the audio and uses an ASCII version of the International Phonetic Alphabet. Espeak is a traditional text- to - speech program that takes the orthographical form of a word and produces its pronunciation. 

-In IpaSpeak (the front-end) we bypass the orthographical interpretation step, and simply accepts Ipa characters as the input. IpaSpeak was written and compiled in Qt 5.5. Currently the windows version is statically built whilst the linux version requires installation of the qt libraries.

/Requirements

Qt 5.5

Qt 5.5 static libraries (optional, you need this if you want to create your own static versions of the application)

v1.00 - We are using espeak-v1.48.04 as the speech engine

/Functionality Extensions

Additional IPA character support: - If you would like to support other Ipa characters you can add them to the Ipa lookup table located in "IpaString.cpp". Note that adding character support does not mean you are supporting the phonemes, corresponding phonemes must exist within the speech synthesizer espeak as well.

Additional Phoneme support: - To support new phonemes you will need to develop espeak (http://espeak.sourceforge.net/)

/Other

If you have any comments/queries/suggestions please contact us at ipaspeak@hotmail.com
