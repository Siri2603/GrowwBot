# GrowwBot
facts only bot 
Groww MF FAQ Bot
A lightweight, facts-only FAQ chatbot for a small set of Groww Mutual Fund schemes.
It runs entirely in the browser — no build step, no backend, no dependencies beyond a
Google Fonts stylesheet. Open the HTML file and it works.

⚠️ Unofficial educational prototype. Not affiliated with, endorsed by, or
connected to Groww. Answers reference official AMC / SEBI / AMFI pages only and the
figures shown are illustrative — always confirm live values on the official scheme page.

What it does

Answers factual questions about three schemes: Large Cap Fund, Value Fund, and
ELSS Tax Saver Fund — expense ratio, exit load, minimum SIP, lock-in, riskometer,
benchmark, fund manager, category.
Explains general concepts (SEBI riskometer, what ELSS is) and how to download a
capital-gains statement.
Attaches a source link to every answer.

Guardrails
The bot deliberately refuses three categories of request:

PII — detects and rejects messages containing PAN, Aadhaar, account numbers, email,
phone numbers, or credentials. Nothing is stored.
Advice — won't tell you whether to buy/sell/hold; redirects to a SEBI-registered advisor.
Performance — won't compute, predict, or compare returns; points to the official factsheet.
