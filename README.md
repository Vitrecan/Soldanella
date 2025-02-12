# Soldanella

# Word Mapping Input Module

This module provides a minimal interface for mapping one word to another. It is the first atomic step in our larger word mapping application.

## Files

- **mapping-input.html**:  
  Contains the HTML structure and JavaScript logic for the input fields and the mapping button.


## Overview

The page displays two text inputs:
- **Original Word**: where the user enters the word they want to map.
- **Mapped Word**: where the user enters the word that will be the mapping result.

A button labeled **"Add Mapping"** triggers JavaScript that:
1. Retrieves the values from both input fields.
2. Trims any extra whitespace.
3. Logs the mapping to the console (simulating storage).