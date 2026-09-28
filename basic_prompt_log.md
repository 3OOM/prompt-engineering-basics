# Foundational Prompt Log

## Task 1: Text Summarization

### Prompt Input
```text
Summarize the text below in exactly three bullet points.

Text: "Remote work has rapidly expanded, introducing both opportunities and obstacles for modern businesses. Organizations can access a broader talent pool and reduce office-related costs. However, remote teams may face communication difficulties, reduced team cohesion, cybersecurity risks, and challenges maintaining productivity. Successful remote work requires clear communication policies, appropriate collaboration tools, regular check-ins, and strong data-protection practices."
```

### ChatGPT Output
- Remote work expands access to talent and can reduce office-related expenses.
- Businesses may face communication, collaboration, cybersecurity, and productivity challenges.
- Clear policies, collaboration tools, regular check-ins, and data-protection practices support successful remote work.

## Task 2: Information Extraction

### Prompt Input
```text
Extract the customer's name, email address, and order ID from the support request below.

Support Request: "Hello FlexTime, my name is John Doe (john.doe@email.com). I haven't received my shipment updates for order FT-99881. Please check."

Return the result using the following labels:
- Customer Name
- Email Address
- Order ID
```

### ChatGPT Output
- Customer Name: John Doe
- Email Address: john.doe@email.com
- Order ID: FT-99881

## Task 3: Formatting Conversion

### Prompt Input
```text
Convert the list of product prices below into a Markdown table with two columns: "Item" and "Price".

List:
- Wireless Mouse: $25.00
- Ergonomic Keyboard: $70.00
- Insulated Water Bottle: $18.00
```

### ChatGPT Output

| Item | Price |
|---|---:|
| Wireless Mouse | $25.00 |
| Ergonomic Keyboard | $70.00 |
| Insulated Water Bottle | $18.00 |

## Task 4: Tone Editing

### Prompt Input
```text
Act as an editor. Rewrite the draft text below to sound like a professional, polite B2B email sent to a client.

Draft: "hey, sorry we are late on the report. it had bugs. we will send it tomorrow. thanks."

Include a subject line and a professional email body.
```

### ChatGPT Output
**Subject: Update Regarding the Report**

Dear Client,

Please accept our apologies for the delay in delivering the report. We identified and are resolving several issues to ensure that the final version meets the expected quality standards. We expect to send the completed report tomorrow.

Thank you for your patience and understanding.

Best regards,  
[Your Name]

## Task 5: Constraint-Driven Output

### Prompt Input
```text
Summarize the sentence below in under 20 words. Do not use the word "help" or "assist".

Sentence: "Our customer success managers are available 24 hours a day to guide new users and resolve technical account disputes."
```

### ChatGPT Output
Customer success managers provide round-the-clock guidance and resolve technical account disputes for new users.
