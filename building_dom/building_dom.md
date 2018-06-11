### Building of Document Object Model

#### Generic steps to build DOM
~~~~~

     (Characters) HTML Tags (<html>,<head>) written in the HTML file
          |
      (Tokens)    tokenizer converts html tags to tokens
          |       like [StartTag: HTML][StartTag: HEAD] which helps in building node tree
          |
       (Nodes)    Here tokens are arranged in a tree structure (node object)
          |       to get the relationship between those tokens (parent, child, etc.)
          |
        (DOM)     DOM is simply a node object with all contents and properties(passed through HTML file)

~~~~~
[Explanation Link](https://css-tricks.com/dom/)
