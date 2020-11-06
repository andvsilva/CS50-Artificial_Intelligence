# CS 50 Artifical Intelligence with python
- [CS50-AI](https://cs50.harvard.edu/ai/2020/)
## Lectures

[Lecture 0 - Search](search):
- **Uninformed search**: Search strategy that uses no problem-specific knowledge
  - Depth First Search ```StackFrontier()```
  - **Breadth First Search** ```QueueFrontier()``` (more efficient)

    ##### [Project 0](https://cs50.harvard.edu/ai/2020/projects/0/): 
    - [Degrees](search/degrees/): Write a program that determines how many “degrees of separation” apart two actors are.
        ```bash
        $ python degrees.py large
        Loading data...
        Data loaded.
        Searching...

        Name: Emma Watson
        Name: Jennifer Lawrence
        3 degrees of separation.
        
        1: Emma Watson and Jennifer Connelly starred in Noah
        2: Jennifer Connelly and Ed Harris starred in A Beautiful Mind
        3: Ed Harris and Jennifer Lawrence starred in Mother!
        ```