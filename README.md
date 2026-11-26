# Data Wrangling - Practice Sheet (Pandas)

Pandas Data Wrangling ke 30 practical questions, Google Colab par banaye hain.

## Sections
- **Section A (Easy):** Q1 se Q15
- **Section B (Moderate):** Q16 se Q25
- **Section C (Hard):** Q26 se Q30

## Topics
- Merge: `inner`, `left`, `right`, `outer` joins
- `pd.concat()` (`axis=0`, `axis=1`, `ignore_index`, `join='inner'`)
- `combine_first()` aur `combine()` (`np.maximum` vs `np.fmax`)
- Reshaping: `pivot()`, `pivot_table()`, `stack()`, `unstack()`, `reset_index()`
- Missing values (NaN) aur duplicate entries ka effect

## Files
| File | Description |
|------|-------------|
| `data_wrangling.ipynb` | Colab notebook (har question ka alag cell, output ke saath) |
| `data_wrangling.py` | Same code, normal Python file |
| `data/` | Original CSV files (students_master, exam_marks, semester_enrollments, section_CA, section_CB, marks_original, marks_updated, marks_long, repeat_tests) |

## Kaise run karein
1. `data_wrangling.ipynb` ko [Google Colab](https://colab.research.google.com) me kholo
2. `Runtime -> Run all` dabao

Notebook ke pehle cell me saari CSV files apne aap ban jaati hain, alag se upload nahi karni padti.

Local me chalane ke liye:

```bash
pip install pandas numpy
python data_wrangling.py
```
