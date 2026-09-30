# Question 2: Prompting Techniques

## 1. Zero-Shot Prompting
### Prompt
Classify the sentiment of the following customer review as Positive, Negative, or Neutral. Do not provide any reasoning, just return the sentiment label.

Review: "The product arrived two days late and the packaging was torn, but the customer support representative was very polite and issued a partial refund immediately."

### Executed Output
Neutral

---

## 2. One-Shot Prompting
### Prompt
Convert the given informal text into professional corporate email language.

Example:
Informal: Hey, I won't be able to make it to the meeting today. Catch you later.
Professional: Dear Team, I will be unable to attend today's meeting due to a scheduling conflict. I will follow up via email with my updates.

Task:
Informal: Thanks for the help yesterday, the presentation went super well and everyone liked it!
Professional:

### Executed Output
Dear Team, thank you for your assistance yesterday. The presentation was well-received by all attendees, and I appreciate your support.

---

## 3. Few-Shot Prompting
### Prompt
Extract the product name and price from the given text into JSON format.

Example 1:
Text: I bought a mechanical keyboard for $85 at the electronics store.
JSON: {"product": "mechanical keyboard", "price": "$85"}

Example 2:
Text: The noise-canceling headphones were on sale for $120.
JSON: {"product": "noise-canceling headphones", "price": "$120"}

Example 3:
Text: She paid $450 for a refurbished laptop online.
JSON: {"product": "refurbished laptop", "price": "$450"}

Task:
Text: He picked up an ergonomic gaming mouse for $60 yesterday.
JSON:

### Executed Output
{"product": "ergonomic gaming mouse", "price": "$60"}