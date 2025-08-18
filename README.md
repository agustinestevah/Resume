A resume template + an auto compiler that compiles the pdf in the root of the directory once overleaf code is pushed. The way it is structured:

1) A .tex is made in Overleaf (or any other LaTeX software) and pushed to this repo
2) The Github Action recognizes the push and will act to compile
3) It will compile the new and improved resume to Github
