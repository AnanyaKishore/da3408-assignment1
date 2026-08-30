# Use of AI

**Tools used:** Claude, Gemini

**How they were used:**
1. Identifying syntax to suppress MLflow warnings for questions 2 and 4, and to brainstorm what changes were to be made to the training code for the MNIST dataset, based on the provided starter code. I manually reviewed to remove excessive code and debug wherever I ran into problems.
2. Generating the environment.yml for question 4, based on the dependencies I provided to it.
3. Discovering the following commands (for question 3):
   * `find data -type f | head -n 2800 >> dataset.csv` writes the names of all files in data/ to dataset.csv
   * `wc -l dataset.csv` outputs the number of lines in a CSV file
4. Identifying the need to install awscli to set up a remote AWS S3 storage, and its associated commands
5. Identifying git commands to compress various related, trivial commits into a single one
6. Identifying the difference between a local SSH remote and what is required in question 3

**Impact:**  

While I did not find that AI aided with significantly reducing the time spent on the coding aspect considering that I manually reviewed and corrected the generated code, it was a great help for when I ran into errors on the terminal, saving me many hours of debugging.