# classification-program

This script allows you to input pH and Brix values for sugar samples,  
and it classifies them as either **Real Fresh Sugar** or **Not Real Sugar**  
based on a simple threshold rule.

## How It Works

- If the pH ≤ 6.42 **and** Brix ≤ 19.5 → classified as `Real Fresh Sugar`.
- Otherwise → classified as `Not Real Sugar`.

## Files

- `classify_sugar.py` — Main interactive script.

## How to Run

Run the script from your terminal:

```bash
python classify_sugar.py

