<center>
<img width="627" height="253" alt="hax-planet" src="https://github.com/user-attachments/assets/025cbad7-a27a-4da0-84ff-36b655813bc4" />
</center>

# Zalgo Text Generator


T̫̈̀ḁ̵̯͚̘̺͌̑͐k̶͚̟̪͙̩̗͐ͅe̶̳̝̺̥͋͘ o̘͔̹̱v̴̥̬̟̰e̴̷̘̙̳͒̆r̶̬̟̅ t̺̆h̷̘e̷̵̛̺̟̖̬̼͊̓ w̸̷̭̱̅͌̕ǒ̺͙̳̻̯̝͌r̬͊l̷̷͔̺̙̎͌̀̕d̷̫͂͑̿̕ w̸̼͑͌́̓i̴̗̱̿̎̈́̕t͕̰̘̯͋̊ͅh̷͖͓̦̫̱͊ g͔̪ñ̸̮̠͘ͅǟ̵̸̶̮̼͐͘r͔̳̂̅̄̍͂͑̕l̺̙͓̩͕̠̰͊̕ẙ̶̦̟͑ g̷̈́l̸̘̺͑͋̅i̶͚̝̺̹͋͊ͅt̟̻̰̅̀͊͋͘c͌̎̐͑͊̊̕h͔̘͒e̷̱̺̪̝͑̅́̿͘d̵͙̯͖̈́͊ t̵̻̮͓̩̞̳̀̆̓ḙ̷̹̦̥̞̀̓̃͊x̯̱̩̤͒̎́̈́t̷̼!̻


Terminal-based zalgo text generator that adds Unicode combining diacritical marks to text for a "glitched" visual effect.


## Requirements

Python3 on system and in path.


## Usage

```bash
# Direct text
zalgo "Your text here"

# From stdin
echo "Hello" | zalgo

# Adjust intensity (default: 5)
zalgo -i 10 "Very glitchy"
zalgo -i 1 "Subtle"

# Control mark positions
zalgo --no-up "No marks above"
zalgo --no-down "No marks below"
zalgo --no-mid "No mid marks"

# Save to file
zalgo -o output.txt "Your text"
```


## Options

- `-i, --intensity N` - Number of marks per character (default: 5)
- `--no-up` - Disable marks above characters
- `--no-down` - Disable marks below characters
- `--no-mid` - Disable mid marks
- `-o, --output FILE` - Write output to file


## Note

Output includes 5 blank lines above and below to prevent terminal prompt overlap with the zalgo effects.
