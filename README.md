# word-thing

This is a set of data for a project I'm making that concerns words and their divisions, specifically syllabically and etymologically.

## Data structure
The data follows this structure,
```
{
    "words": [
    {
       "word": "disestablishmentarianism",
       "syllabic": [0, 3, 5, 8, 12, 15, 18, 19, 20, 22, 24],
       "etymological": [0, 3, 12, 17, 22],
       "prefix": ["dis"],
       "root": ["establish"],
       "suffix": ["ment", "arian", "ism"],
       "phonetics": ["/dɪs/", "/ε/", "/stæb/", "/lɪʃ/", "/mεnt/", "/eɹ/", "/i/", "/ən/", "/ɪz/", "/m/"]
    },
    {
       "word": "insuffrable",
       "syllabic": [0, 2, 5, 8],
       "etymological": [0, 2, 7],
       "prefix": ["in"],
       "root": ["suffer"],
       "suffix": ["able"],
       "phonetics": ["/ɪn/", "/səf/", "/ɹə/", "/bʌl/"]
   }
]}
```

There are 6 entries per word, those being:
- the word.
- the beginning indices of each syllable.
- the beginning indices of each etymological unit.
- the prefix(es).
- the root(s).
- the suffix(es).
- the phonetically written syllables (in an array).

Now, I'm absolutely sure that this method is not the best it could be. If you have suggestions on how it could be improved, PLEASE propose the idea.
If you're interested in contributing in any way, tell me, and I'll add you to the repository. Then just make a branch and add whatever you want !
Oh, and, to contact me for this purpose, find me on Discord, @quantumkya. (Although if you're reading this, I probably shared this to you over Discord already.)
