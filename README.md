# XAI-Decathlon-Round-1-Individual-Method-Trial

Individual method trial notebook for the XAI Decathlon (Round 1).

## Setup

```bash
cd ~/Desktop/XAI-Decathlon-Round-1-Individual-Method-Trial
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Run the notebook

```bash
source .venv/bin/activate
jupyter notebook xai_decathlon_kedar.ipynb
jupyter notebook xai_decathlon_Jaideep.ipynb
jupyter notebook xai_decathlon_Oge.ipynb
```

Or open a notebook in Cursor/VS Code and select the kernel **Python (XAI Decathlon)**.

## First steps

1. Run the **Setup** cell and the tabular/image model cells.
2. Fill in your assigned method in the Results Table.
3. Implement your method in each Event workspace cell.

## Notebooks

All three individual trials use **LIME** as the assigned method.

| Student | Notebook | Events covered |
|---|---|---|
| Oge Ezenwa | `xai_decathlon_Oge.ipynb` | 1–3 |
| Jaideep Aher | `xai_decathlon_Jaideep.ipynb` | 4–6 |
| Kedar | `xai_decathlon_kedar.ipynb` | 7–10 |

`xai_decathlon_events123.ipynb` is Oge's working draft for Events 1–3 (superseded by `xai_decathlon_Oge.ipynb`).

`xai_decathlon.ipynb` is the merged team notebook combining all three individual trials into a single Results Table covering Events 1–10.
