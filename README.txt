README - AI-Enabled Digital Marketing with Prompt Engineering

1. Requirements:
- Python 3.x
- Install the following libraries:
  pip install openai==0.28
  pip install pandas
  pip install python-docx
  pip install textblob
  pip install textstat

2. Files Included:
- main_script.py (Main code)
- platform_weights_generator.py (Training script)
- usage_data.xlsx (Training dataset)

3. How to Use:
- First, run `platform_weights_generator.py` to train and save the model.
- This will create a file named `platform_weights.pkl`.
- Then run `main_script.py` and follow the prompts.

4. Important:
- Change the file paths in `COMM2019_Project_File` (look for Word and Excel output lines) to valid paths on your system where you want the files saved.
- You can find this section in the lower end of the code
- Sample path: "C:\Users\Vidur\OneDrive\Desktop\marketing_campaign_calendar.docx"
- Do ensure that you name the file like 'marketing_campaign_calendar.docx' and 'marketing_campaign_calendar.xlsx' after the path, otherwise, the file will not be generated

5. Note:
- Make sure `platform_weights.pkl` and `usage_data.xlsx` are in the same folder as the code.
