# Research log Aleksandar Dzudzevic

### Research Day 1: Oct.28 2024

- Finished Rustlings hashmaps
- Finished Rustlings Quiz2
- Finished Rustlings options
- Finished Rustlings errors
- Learned about
- Learned how to better use Option and Result enum and learned about wrapping values in Some()
- Started the undergrad exercise and passed first 2 tests.
- Committed and pushed on GitHub

### Research Day 2: Nov.1st 2024

- Undergrad exercises project methods for swapping, displaying, checking if the tiles are unique, performing move or multiple moves.
- learned about !write() and !format() macros and what {:>2} means in !write macro
- learned about dereferencing using \*
- Finished 2 chapters of Rustbook (Generics Ch 10, Writing automated Testing Ch 11)
- Finished 1 section of rustlings (generics)
- Committed and pushed on GitHub

### Research Day 3: Nov.4th 2024

- Finished rustlings traits section
- Finished rustlings lifetimes section
- Wrote test cases for test_validate_game_state, test_swap, test_perform_move, test_perform_moves methods
- Finished Quiz 3 of Rustings
- Finished testing section of rustlings
- Code Review
  - Helped method for finding the empty tile
  - Updated all_tiles_are unique method so that it also ensures that the tile doesn’t contain a value that isn’t allowed.
  - Fixed the col row mistake in my perform move method
- Worked on the from_str method
- Learned about lines() and collect() methods in Rust

### Research Day 4: Nov.8 2024

- Finished Rustlings section 18 iterators (iter, collect, )
- Fixed the from_str indexing issue I had with rows and columns
- Worked on the from_str method and learned about how to utilize the boolean return of the insert method for HashSets to either insert something that wasn’t in the HashSet originally or return that it already exists without using contains() to make code cleaner.
- Used the iter method I learned from rustlings in from_str when traversing rows and columns to make accessing tiles part cleaner
- The used collect method I learned from Rustlings exercises to store values extracted from the str inside of a vector.
- Added new test cases for from_str and found an error in my solution for cases of multiple empty tiles
- Fixed from_str method by implementing empty tile count and returning None if it exceeds 1
- Started with shortest_path method
- learned about filter_map functionality
-
- Committed and pushed on GitHub
