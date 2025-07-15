# Network Analysis and Sentiment Exploration of "Best Books of the 21st Century"
This project analyzes the "Best Books of the 21st Century" dataset from The New York Times using network analysis and natural language processing techniques. The goal is to uncover relationships between books based on public ballots and analyze the sentiment expressed in blurbs written by Times staff and voters.

## Project Overview
### Data Sources:

Rankings data: Information on 100 selected books including one or two blurbs per book.

Ballots data: Votes from 51 "literary luminaries," each submitting their top 10 books.

### Methods:

Built a bipartite graph representing connections between voters and books.

Created a projection to identify pairs of books frequently voted together.

Applied the island method to filter the network by increasing the threshold of shared voters until no books remained.

Conducted sentiment analysis on book blurbs to determine:

Books with the highest counts of positive and negative words

Books with the greatest percentage of positive words

Explored common positive and negative words to identify nuances and areas for deeper semantic context analysis.

### Key Insights and Conclusions
Network analysis revealed clusters of books that shared many voters, highlighting communities of reader preferences.

Sentiment analysis pointed out books with notably positive or negative language in their blurbs, offering insight into public and editorial perceptions.

Initial word-level sentiment scoring showed limitations, such as context-dependent word meanings (e.g., "work" and "fiction"), suggesting the need for more advanced semantic methods in future research.

## Collaborators
This project was completed in collaboration with:

[Marley Myrianthopoulos]

[Molly Siebecker]
