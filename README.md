# ff7-ff14-dialogue-corpus
This is a corpus of all the dialogue in Final Fantasy 7 and Final Fantasy 14, scraped and parsed.

**Process**
I used BeautifulSoup and other Python libraries to scrape the HTML of webpages containing the script of each game. I organize the data into the following files:

| Game                        | File Name                          | Source                                             |
|-----------------------------|------------------------------------|----------------------------------------------------|
| **Final Fantasy 7 (FFVII)**  | ff7-chapters.txt                   | [Source](https://www.yinza.com/Fandom/Script/)    |
|                             | ff7-mission-text.txt              |                                                    |
|                             | ff7-characters.txt                |                                                    |
|                             | ff7-dialogue.csv                  |                                                    |
|                             | ff7-character-summary.csv         |                                                    |
|                             | *ff7-character_name-dialogue.txt   |                                                    |
| **Final Fantasy 14 (FFXIV)** | ff14-sections.txt                 | [Source](https://xiv.quest/)                      |
|                             | ff14-quests.txt                   |                                                    |
|                             | ff14-item-text.txt                |                                                    |
|                             | ff14-characters.txt               |                                                    |
|                             | ff14-dialogue.csv                 |                                                    |
|                             | ff14-character-summary.csv        |                                                    |
|                             | *ff14-character_name-dialogue.txt  |                                                    |

*One of these was created for each unique character in the game.
