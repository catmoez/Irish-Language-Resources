This is an Irish language word list of 20,232 terms.

The Irish word list is generated partly from two smaller previous lists I found: Michal Boleslav Měchura's list, 2015, https://github.com/michmech/irish-word-frequency; and an uncredited Google Doc at https://docs.google.com/spreadsheets/d/1A6FUrSO_Y-GhyuZNnho97AeE0f4kRucWH3HYpOXR3xY/edit?gid=0#gid=0; both accessed 15 Jan. 2025. Source is marked as 'mm' if from the Mechura list (n = 6.4k); 'gdoc' if from the Google document (n = 1.2k); and 'cm' if I have added it from the Irish parliamentary speeches (n = 12.5k).

Additional words are added via letter combination and symbol (accent) searches in 20 years of Dáil Éireann transcripts, from 2004 to the end of 2024. Transcripts are scraped from kildarestreet.com.

Corpus frequencies and rankings reflect only the word's frequency in the Dáil corpus, and not any frequencies in the previous word lists. The majority of speeches are in English, which is why some words valid in both languages (do, go, etc.) are scored so highly. You can remove these if desired, using the 'English' binary variable.

The 'English' column reflects whether an Irish word is (also) valid in English, per passing either a US English or GB English spellcheck in the R hunspell package.

All words are lowercased, but not lemmatized. Please note that proper nouns such as place names and people's names may remain in the data, although I have done several pass-throughs to remove URLs, words from other languages, and well-known proper nouns (Nestle, etc.).

---

A second CSV will add Google Translate translations of the wordlist.

Please credit if using:

Moez, Catherine. 2025. "Irish Language Wordlist". Github. Available at: https://github.com/catmoez/Irish-Language-Resources. 

@misc{cm2025irish,
 author = {Moez, Catherine},
 year = {2025},
 title = {Irish Language Wordlist},
 url = {https://github.com/catmoez/Irish-Language-Resources},
 urldate = {16.01.2025}
}

