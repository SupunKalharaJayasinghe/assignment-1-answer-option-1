# Assignment 1 Answer: Option 1

## Student / Submission

- Registration Number: IT23585744
- Option: Option 1 - Transliteration Accuracy Testing

## Folder Structure

```text
IT23585744/
├── IT23585744.py
├── IT23585744.xlsx
└── ITXXXXXXXX_repository_link.txt.txt
README.md
```

## How to Install Dependencies

Open Command Prompt or PowerShell in the folder that contains the Python file and Excel file.

If you are inside the main project folder, go into the submission folder first:

```bash
cd IT23585744
```

Then install the required Python packages:

```bash
pip install playwright openpyxl
playwright install
```

## How to Run the Test Automation

Make sure `IT23585744.py` and `IT23585744.xlsx` are inside the same folder.

Run this command from inside the `IT23585744` folder:

```bash
python IT23585744.py --excel "IT23585744.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1
```

## How to Check Results

After the script finishes, open:

```text
IT23585744.xlsx
```

Check the following columns:

- Actual output
- Status
- Singlish input types covered
- Evidence or rationale for the input type covered
