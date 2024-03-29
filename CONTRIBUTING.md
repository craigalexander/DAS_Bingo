Add your own card to extend our range of bingo cards! If you'd like to add a card, simply submit a [pull request](https://help.github.com/articles/using-pull-requests) following these guidelines:
- Create an R file under the [`inst/topics/`](./inst/topics/) directory
- The name of the R file will be used as the name of the topic of bingo cards
- The file should return a character vector containing the words or phrases to put in the squares
- There should be at least 24 squares, in order to make 5 x 5 bingo cards
- Optional: at the top of the file, add your name and a short description of the card as a comment
- You can look at the [existing examples](./inst/topics/) 

We'll try to be as responsive as possible in reviewing and accepting pull requests. We appreciate your contributions!
