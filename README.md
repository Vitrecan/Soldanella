# Soldanella

# Word Mapping Input Module

This module provides a minimal interface for mapping one word to another with local persistence.

## Features
- Persistent storage using browser localStorage
- Data survives browser/tab restarts
- No cloud dependencies
- Automatic data saving

## Files

- **mapping-input.html**:  
  Contains the HTML structure and JavaScript logic with local persistence using:
  - `localStorage` for offline data storage
  - Observer pattern for state management
  - Input validation and sanitization

## Data Persistence
Mappings are automatically saved to browser's localStorage and will persist:
- Between page refreshes
- After browser/tab closure
- Across browser restarts

## Development Principles
- **YAGNI**: Only localStorage implementation added (no IndexedDB/WebSQL)
- **SOLID**: Single responsibility for storage handling
- **KISS**: Simple localStorage API usage
- **DRY**: Centralized storage handling in MappingStore