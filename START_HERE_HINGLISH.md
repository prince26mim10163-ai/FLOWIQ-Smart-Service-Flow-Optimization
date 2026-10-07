# FLOWIQ - Sabse pehle ye padho

Tension lene ki zarurat nahi hai. Maine tumhare liye project ko ek complete bundle ke form mein organize kar diya hai.

## Tumhare paas kya-kya hai?

### `main.py`
Ye **main project** hai. Isko run karoge to FLOWIQ ka menu open hoga.

### `FLOWIQ.py`
Ye **single-file version** hai. Agar submission portal sirf ek `.py` file accept karta hai, ise use kar sakte ho.

### `flowiq/`
Is folder mein actual project ka modular code hai. `main.py` isi folder ko use karta hai.

### `demo.py`
Ye automatic demo chalata hai. Teacher ko jaldi project dikhane ke liye useful hai.

### `self_test.py`
Ye check karta hai ki project ke main features sahi chal rahe hain.

### `docs/FLOWIQ_Project_Report.docx`
Formal report. Bas apna Name, Registration Number, Section, Faculty aur Date fill karna hai.

### `docs/FLOWIQ_Project_Report.pdf`
Report ka ready PDF version.

### `presentation/FLOWIQ_Project_Presentation.pptx`
Ready presentation. Apni academic details add kar dena.

### `notebook/FLOWIQ_Demo.ipynb`
Jupyter Notebook demo.

### `PROJECT_VIVA.md`
Viva mein kya bolna hai aur teacher kya pooch sakte hain.

### `SUBMISSION_GUIDE.md`
Kaunsi file kis kaam ki hai aur kab kya upload karna hai.

## Abhi tumhe kya karna hai?

### Step 1
ZIP extract karo aur `FLOWIQ_Submission` folder VS Code mein open karo.

### Step 2
Terminal kholo aur run karo:

```bash
pip install numpy
```

### Step 3
Sabse pehle automatic demo:

```bash
python demo.py
```

### Step 4
Phir actual interactive project:

```bash
python main.py
```

### Step 5
Final check:

```bash
python self_test.py
```

Output aana chahiye:

```text
ALL FLOWIQ SELF-TESTS PASSED
```

## Teacher ko demo kaise dikhana hai?

Pehle `python demo.py` run karo.

Phir `python main.py` mein:

`1` -> Live Dashboard  
`3` -> New Request  
`4` -> Smart Counter Recommendation  
`7` -> What-If Simulation  
`8` -> Counter Capability Pairs

## Report mein kya bharna hai?

Sirf ye fields:

- Student Name
- Registration No.
- Section
- Faculty
- Submission Date

Baaki report ready hai.

## Important

Screenshot mein tumhara VITyarthi Python Essentials course visible tha, lekin separate project rubric/instructions visible nahi the. Isliye maine package ko general submission-safe format mein banaya hai aur `SUBMISSION_GUIDE.md` mein exact role of every file explain kiya hai.

## Project ka simple meaning

FLOWIQ ka kaam hai:

```text
Request
   -> Priority
   -> Eligible Counter
   -> Lowest Workload
   -> Estimated Wait
   -> Queue Update
```

Aur later yahi Python engine actual web/mobile/company product ka foundation ban sakta hai.
