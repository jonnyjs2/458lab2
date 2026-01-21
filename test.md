# Comparing Trading Card Game Communities Through Text Analysis

## Topic and Search Parameters

This project explores and compares three Trading Card Games (TCGs): **Pokémon**, **Riftbound**, and **Magic: The Gathering**. While all three are collectible card games, they differ in age, popularity, competitive depth, and audience. The goal of this research is to examine how these differences are reflected in the language used by their communities.

Text data for each game was collected using keyword-based searches focused on online discussions and descriptions related to each TCG. Search parameters included:
- Game-specific identifiers (e.g., *Pokémon*, *Magic: The Gathering*, *Riftbound*)
- Gameplay-related keywords such as *cards*, *deck*, *strategy*, *meta*, and *play*

Each dataset was stored as a CSV file and used to generate a word cloud representing the most frequently occurring terms for each game.


## Why I Chose to Make This Comparison

I chose to compare these three games because they all belong to the same genre but represent very different stages of maturity and community development. Pokémon and Magic: The Gathering are long-established franchises with massive global player bases, while Riftbound is a newer and less mainstream TCG.

By comparing them, I wanted to see whether established games show more complex or specialized vocabulary compared to newer games, and whether community focus (competitive play vs. collecting vs. casual play) can be observed through text analysis. This comparison helps highlight how game design, history, and audience shape online discourse.


## Comparison of the Word Clouds

The word clouds reveal both similarities and differences among the three TCGs:

- **Pokémon** prominently features words related to collecting, rarity, and specific characters or card types, reflecting its strong emphasis on collection and brand recognition.
- **Magic: The Gathering** shows a higher frequency of strategy-oriented terms such as *deck*, *format*, *mana*, and *competitive*, indicating a more complex and strategically focused community.
- **Riftbound** has a smaller and more general vocabulary set, with recurring words related to gameplay basics and exploration, suggesting a developing player base and evolving meta.

Across all three word clouds, common terms like *deck*, *meta*, and *game* appear frequently, reinforcing their shared identity as TCGs.


## Possible Reasons for Observed Patterns

The observed patterns are likely influenced by each game’s history and player demographics. Pokémon’s strong branding and appeal to collectors explain the prominence of character- and rarity-related terms. Magic’s long competitive history and complex ruleset contribute to the dominance of technical and strategic vocabulary. Riftbound’s simpler and less specialized word cloud likely reflects its newer status and smaller, less established community.

Additionally, the amount of available online discussion and documentation for each game plays a major role in shaping word frequency and diversity.


## How This Research Could Be Improved

This research could be improved by expanding the data sources to include more platforms, such as Reddit, forums, and social media posts. Increasing the sample size would provide a more representative view of each community. Future work could also involve:
- Removing or standardizing common filler words more aggressively
- Separating competitive and casual discussions
- Performing sentiment analysis in addition to word frequency analysis

These improvements would allow for deeper insights into community attitudes and engagement.


## Unexpected Findings and Observations

One unexpected finding was how strongly strategy-related terminology dominated the Magic: The Gathering word cloud compared to Pokémon. I initially expected more overlap between the two established games, but Pokémon’s focus leaned much more toward collecting and branding than competitive play. Additionally, Riftbound showed less vocabulary diversity than expected, highlighting how much community maturity impacts online discourse.


## Repository Contents and Data Access

- The generated **word cloud images** for Pokémon, Riftbound, and Magic: The Gathering have been exported and added to this repository.
- These images are embedded below for direct comparison.
- The **CSV files** containing the collected text data and processed results are available for download at the following links:

**Download CSV files:**
- [Pokemon Data CSV](/assets/pokemon.csv)
- [Riftbound Data CSV](/assets/riftbound.csv)
- [Magic the Gathering Data CSV](/assets/magic.csv)


## Word Clouds

### Pokémon
![Pokémon Word Cloud](/img/pokemon.png)

### Riftbound
![Riftbound Word Cloud](/img/riftbound.png)

### Magic: The Gathering
![Magic the Gathering Word Cloud](/img/magic.png)
