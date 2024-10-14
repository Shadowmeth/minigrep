# minigrep
minigrep is a simple grep like tool that searchs for query text in a file and prints all the lines containing the text.

## Usage
First clone the project
```
git clone https://github.com/Shadowmeth/minigrep
cd minigrep
```
Then run the project with
```
cargo run -- to poem.txt
OR
IGNORE_CASE=1 cargo run -- to poem.txt
```
This will print all the lines of poem.txt containing the string "to".</br>
Set IGNORE_CASE environment variable for case insensitive search.</br>
For now only case sensitive search provides colored output (matched text will be colored red).
