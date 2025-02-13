# Soldanella

# Word Mapping Input Module

This module provides a minimal interface for mapping one word to another. It is the first atomic step in our larger word mapping application.

## Files

- **mapping-input.html**:  
  Contains the HTML structure and JavaScript logic for the input fields and the mapping button.


## Overview

The page displays two text inputs:
- **Original Word**: where the user enters the word they want to map.
- **Mapped Word**: where the user enters the word that will serve as the mapping.

There are two buttons:
1. **Add Mapping**: When clicked, it validates the inputs, adds the mapping as an object to a global array, and logs the mapping.
2. **Submit Mappings**: When clicked, it logs the entire array of mappings (simulating a submission).

## Test Case

1. Enter "test1" as the original word and "test2" as the mapped word, then click **Add Mapping**.
2. Add another mapping (e.g., "hello" -> "world").
3. Click **Submit Mappings**.
4. Check the browser console for the logged mappings array.