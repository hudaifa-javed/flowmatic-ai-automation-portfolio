# flowmatic-ai-automation-portfolio
AI Automation projects built for real business use-cases
# Flowmatic — AI Automation Portfolio

Real, tested AI automation projects built for actual business use-cases. 
Each project below solves a genuine business problem using AI + no-code automation tools.

📄 Full case studies with business impact: [View on Notion](https://app.notion.com/p/Flowmatic-AI-Automation-Portfolio-3db68afcc5888009aee4d5b5cc4181aa?t=3db68afcc588807b95b300a95a2b0234)

---

## Project 1: AI-Powered WhatsApp Lead Bot

**Problem:** Businesses lose leads because they can't reply to WhatsApp messages instantly, 24/7. Manual replies are slow and inconsistent.

**Solution:** An automated pipeline that receives a customer's WhatsApp message, generates a smart AI-powered reply based on the business's tone/instructions, logs the lead, and sends the reply back — all within seconds, no human needed.

**Tech Stack:** Make.com, Meta WhatsApp Business Cloud API, Google Gemini AI, Google Sheets

![WhatsApp Lead Bot Workflow](whatsapp%20lead%20automation.png)

**How it Works:**
1. Customer sends a WhatsApp message → Webhook receives it
2. Google Gemini AI reads the message and generates a professional, on-brand reply
3. Lead details (name, number, message, timestamp) are logged into Google Sheets
4. AI-generated reply is sent back to the customer via WhatsApp API

**Result:** Fully automated, tested end-to-end lead response system — reduces response time from hours to seconds, works even outside business hours.

---
## Project 2: AI Customer Support Ticket Classifier

**Problem:** Support teams waste time manually reading every customer ticket to figure out what it's about and how urgent it is — this delays response to critical issues.

**Solution:** An automated system that receives a customer support message, uses AI to instantly classify it by category and priority level, and logs it in an organized format — so teams can act on urgent tickets first.

**Tech Stack:** n8n, Google Gemini AI, Google Sheets

![AI Ticket Classifier Workflow](AI%20ticket%20classifer%20automation.png)

**How it Works:**
1. Customer support message comes in via Webhook
2. Google Gemini AI analyzes the message and classifies it (category + priority)
3. A Code node parses the AI's response into clean structured data
4. Ticket details (customer name, email, message, category, priority) are saved to Google Sheets

**Result:** Instant, consistent ticket triage — no more manual sorting, urgent issues get flagged automatically.
