# ff7-ff14-dialogue-corpus
This is a corpus of all the dialogue in Final Fantasy 7 and Final Fantasy 14, scraped and parsed.

**Process**
I used BeautifulSoup and other Python libraries to scrape the HTML of webpages containing the script of each game. I organize the data into the following files:

| Game                        | File Name                          | Description                                                              | Source                                             |
|-----------------------------|------------------------------------|--------------------------------------------------------------------------|----------------------------------------------------|
| **Final Fantasy 7 (FFVII)**  | ff7-chapters.txt                   | Chapters of the game.                                                   | [Source](https://www.yinza.com/Fandom/Script/)    |
|                             | ff7-mission-text.txt              | Text for missions.                                                       |                                                    |
|                             | ff7-characters.txt                | Information on characters.                                               |                                                    |
|                             | ff7-dialogue.csv                  | Dialogue data in CSV format.                                             |                                                    |
|                             | ff7-character-summary.csv         | Summarized character data in CSV format.                                 |                                                    |
|                             | ff7-character_name-dialogue.txt   | Character-specific dialogue files. (One for each character)             |                                                    |
| **Final Fantasy 14 (FFXIV)** | ff14-sections.txt                 | Sections of the game.                                                    | [Source](https://xiv.quest/)                      |
|                             | ff14-quests.txt                   | Quest-related text.                                                      |                                                    |
|                             | ff14-item-text.txt                | Item descriptions and texts.                                             |                                                    |
|                             | ff14-characters.txt               | Information on characters.                                               |                                                    |
|                             | ff14-dialogue.csv                 | Dialogue data in CSV format.                                             |                                                    |
|                             | ff14-character-summary.csv        | Summarized character data in CSV format.                                 |                                                    |
|                             | ff14-character_name-dialogue.txt  | Character-specific dialogue files. (One for each character)             |                                                    |

