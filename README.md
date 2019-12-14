#automate
Command Line Dictionary Tool



Create a command-line dictionary tool using this(https://fourtytwowords.herokuapp.com/) API. We prefer the task to be submitted in Node.js. If you are unable to do so, you can use python, ruby or PHP.

API Key: b972c7ca44dda72a5b482052b1f5e13470e01477f3fb97c85d5313b3c112627073481104fec2fb1a0cc9d84c2212474c0cbe7d8e59d7b95c7cb32a1133f778abd1857bf934ba06647fda4f59e878d164


Requirements:

Use node version 7.6+ to support async / await .

The command-line tool should have the following functions - 

1. Word Definitions
        ./dict defn <word>
Display definitions of a given word.

2. Word Synonyms
        ./dict syn <word>
Display synonyms of a given word. 

3. Word Antonyms
        ./dic ant <word>
Display antonyms of a given word. Note that not all words would have Antonyms (End point: /relatedWords). Example words with antonyms: single, break, start.

4. Word Examples
        ./dict ex <word>
Display examples of usage of a given word in a sentence. 

5. Word Full Dict
        ./dict <word>
Display Word Definitions, Word Synonyms, Word Antonyms & Word Examples for a given word.

6. Word of the Day Full Dict
        ./dict
Display Word Definitions, Word Synonyms, Word Antonyms & Word Examples for a random word.

7. Word Game
        ./dict play
The command should display a definition, a synonym or an antonym and ask the user to guess the word. 

Rules:
If the correct word is entered, show success message
Any synonyms of the word(expected answer) should be also be accepted as a correct answer.
If incorrect word is entered, user should be given 3 choices:
(1) Try again
Let the user try again.
(2) Hint
Display a hint, and let the user try again. Hints could be:
Display the word randomly jumbled (cat => atc, tac, tca)
Display another definition of the word
Display another antonym of the word
Display another synonym of the word
(3) Quit
Display the Word, Word Full Dict , and quit.

Areas of Focus
Code quality
Code reuse
Code structure
Use of high-level language features

Notes
Github: It is advised to use git, and push the code to Github. Commit frequently, we would like to see how the code evolved by looking at your commits. Share the public URL to the repo for the submission. 
Formatting: The output should be properly formatted on the console and should show all relevant information based on the command.
Contact: Please write to careers@automate.io for any queries. Make sure that you put the subject of the email as “Backend-Task-Query”.



Created with Dropbox Paper. 
