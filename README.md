# Scriptophrenia

A headless browser automation script to constantly query the page above the 
fold and hammer-on the carouselling of the moods. Scriptophrenia for all.

## Flow

OAuth token exchange, find a MoodTarget by [CriticalCSS][0], jumps up until 
a meaningless struct element is found, runs a text analysis on the local DOM, 
determines all the moods from a tokenized set, cycles through them if an anchor 
is present.

## Subtypes

1. Fixed (Default) Scrambler  
   (Above the Fold or First Form)
2. Non-fixed (Scrolling) Scrambler  
   (Find the Form in the Viewport)
3. Batch Scrambler  
   Simultaneously engage any emojiform that has been loaded.

[0]: https://github.com/addyosmani/critical
