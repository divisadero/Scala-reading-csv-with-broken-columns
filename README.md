# Scala-reading-csv-with-broken-columns
Solving the problem of reading in Scala a csv with broken columns. We discovered that lines were being broken by /r characters.

We deleted in the file all occurrences of '/r/n' chain.

This managed to undone the undesired return carriages, keeping lines together when it was the case.

For the chain deletion you can use a terminal tool or a text editor like Notepad.
