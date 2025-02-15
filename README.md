# Soldanella

# Word Mapping Input Module

This module provides a minimal interface for mapping one word to another. It is the first atomic step in our larger word mapping application.

## Files

- **mapping-input.html**:  
  Contains the HTML structure and JavaScript logic for the input fields, mapping buttons, and a search field for mapped words.

## Overview

The page displays two text inputs:
- **Original Word**: where the user enters the word they want to map.
- **Mapped Word**: where the user enters the word that will serve as the mapping.

There are two main buttons:
1. **Add Mapping**: When clicked, it validates the inputs, adds the mapping as an object to a global array, and logs the mapping.
2. **Submit Mappings**: When clicked, it logs the entire array of mappings (simulating a submission).

Additionally, a search field allows the user to search the mapped words. As the user types, matching mappings are displayed.
