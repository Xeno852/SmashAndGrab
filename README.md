# SmashAndGrab

Do not be dumb. This tool is intended STRICTLY for pedagogical and research purposes only. It is not to be used for any illegal activities.

SmashAndGrab is a specialized tool designed for extracting passwords through a loud and aggressive approach in a very rapid "plug-and-play" fashion. Primarily effective on targets with stored passwords, its operation is very obvious and will attract attention to trained individuals. While it tends to yield outcomes, users should be aware of its limitations and the visibility of its use.
# Usage
For the quickest usage, simply run `./smashandgrab`. This will run an extensive attack which if anything returns positive, it will be stored in /creds/smashX.csv
`./smashandgrab`
Some other usages are as follows:

Flags:  
-s: this flag followed by the name of the scope (predefined or user defined) will run ./smashandgrab only on specific<br>
-f : this flag does a fast grab<br>
-l : this flag will be as loud as possible and run in parallel  
-q: this flag attempts to run as quiet as possible<br>
-u: this flag followed by a string or file, targets only the users that are listed<br>
