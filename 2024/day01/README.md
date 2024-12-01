# My progress on AoC 2024: day 1

Here's my daily analisis of my performance and how I could get better during this year AoC.

| What I did | What I saw others do | General take |
| ---------- | -------------------- | ------------ |
| I made a procedure to load the inputs of the challenge, used 2 dynamic arrays to store both sides of the parsed input, and lastly wrote 2 for loops with the calculations for the solutions | The top 100 users on the leaderboard solved the problems in less than an hour ([one](https://github.com/31b4/advent-of-code-2024/tree/main) even did it in less than 2 minutes) and used the following languages in order: R, Python and Typescript. After reading their code, I get that the key features of these languages that made this challenge easier were type inference, out of the box support for dynamic arrays and methods to operate over them, good std libraries for string handling (parsing), and lastly minimalist syntax (reduced amount of symbols to express the instructions). The environments were prepared with the language corresponding build tools and package managers to speed up the time needed to solve the actual problems. There is a clear separation of concern between fetching the problem, parsing it and solving it, that can be seen in the files of each repo | Nim provides the key features I saw on the other languages, but given that I'm still learning the language and memorizing the std libs, I have to check the manual whenever I don't remember a specific procedure, and that makes me lose time. I need to automate the way get the instructions for the problem, given that the page is not easy on my eyes and it might take a tad longer to load it on a browser (wich renders the whole website) rather than a simple script that only fetch and parse the html for the instructions. Also, I need to separate the process of fetching the input and parsing it, from the process of solving the problem with the given data |