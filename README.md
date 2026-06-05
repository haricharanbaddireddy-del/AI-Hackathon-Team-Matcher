# AI Hackathon Team Matcher 🚀

AI Hackathon Team Matcher is an automation workflow built using n8n that helps create balanced hackathon teams automatically using AI.

The workflow analyzes participant details, generates compatible teams, saves the results, and sends team information through email.

## ✨ Features

- Collects participant data from Google Sheets
- Uses Google Gemini AI to analyze profiles
- Creates balanced teams based on:
  - Skills
  - Experience level
  - Preferred roles
- Assigns roles to team members
- Saves generated teams in Google Sheets
- Sends automated Gmail notifications

## ⚙️ Workflow

Google Sheets  
⬇️  
Format Data  
⬇️  
Google Gemini AI  
⬇️  
Generate Teams  
⬇️  
Update Google Sheets  
⬇️  
Send Emails  

## 🛠️ Technologies Used

- n8n
- Google Gemini AI
- Google Sheets
- Gmail
- JavaScript

## 🚀 How to Use

1. Download the workflow JSON file
2. Import it into n8n
3. Connect your own:
   - Google Sheets account
   - Gemini API key
   - Gmail account
4. Run the workflow

Note: The workflow is ready to use, but users need to add their own credentials because account connections and API keys are not shared.

## 👥 Team Members

- Hari Charan Baddireddy
- Divya Sree Atla
- Rashmika Yenda


## 🔄 n8n Workflow

The automation workflow is available in this repository.

📁 Workflow File:

`AI Hackathon team matcher.json`

Import this JSON file into n8n and connect your own Google Sheets, Gemini API, and Gmail credentials to run the automation.


## 📸 Workflow Screenshot

Below is the complete n8n automation workflow:

![AI Hackathon Team Matcher Workflow](workflow.png)
