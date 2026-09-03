# AI Use Log
- Tool/model & version:
- What I asked for:
- Snippet of prompt(s):
- What I changed before committing:
- How I verified correctness (tests, sample data):


with open("input.txt", "r") as file:
    lines = file.readlines()

for i in range(1, len(lines), 2):
    print(lines[i].strip())
