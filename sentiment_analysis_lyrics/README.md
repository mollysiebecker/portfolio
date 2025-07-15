# Gender Identity and Emotional Expression in Popular Music Lyrics
This project explores the relationship between songwriter gender, artist gender, and emotional expression in lyrics, using Billboard year-end song charts from 1965 to 2024. Popular music has long been used as a barometer of American culture, and this project examines how emotion in lyrics relates to gendered patterns in authorship and performance.

## Summary
Collected Billboard Top 100 year-end songs from 1965–2024 using API requests and scraping

Retrieved songwriter and artist information from Wikipedia and MusicBrainz

Used a pre-trained transformer model (DistilBERT) to predict the primary emotion and emotion scores (joy, sadness, anger, fear, love, surprise) for each song

Calculated the rate of emotion-word usage using nltk

Analyzed how emotional content varies by songwriter gender, artist gender, and genre

## Skills & Tools
Python, transformers, nltk, pandas, scipy, matplotlib, seaborn

## Highlights
Applied multi-label emotion classification to thousands of song lyrics

Conducted statistical tests comparing emotion scores across gender categories

Found that female artists and songwriters are underrepresented in expressions of anger

Showed that artist gender had a stronger association with emotional content than songwriter gender

Identified that songs by female artists contained a higher rate of emotional language and received higher classifier confidence scores

## Research Paper & Presentation
This project was also submitted as a [research paper](./capstone_final_paper.pdf) and [presentation](./capstone_presentation.pdf) for a data science capstone.

