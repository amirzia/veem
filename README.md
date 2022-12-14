# Veem
A text editor similar to `VIM` for mortal people.

# Compile
```
cmake -S . -B build
cmake --build build
```

# Usage
Start the program with `./out`. To exit, issue `<CTRL-C>`.

# Test
After compiling, issue `ctest --test-dir build/tests`

# Features to be implemented
- [ ] Read, edit, and save files.
  - `i`: insert mode, `:wq`: save and exit, `:13`: go to line 13.
- [ ] Use cmake and gtest.
  - CI and test coverage.
  - Unit test, integration test, and performance test.
- [ ] Implement 4 different backends and compare their performance:
  1. [ ] Simple string
  2. [ ] Linked list
  3. [ ] Rope
  4. [ ] Gap buffer
