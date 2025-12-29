# 📚 Book Automation Master Prompt

> Turn any idea into a published book in 10 minutes with AI automation

## ✨ Quick Start: Fill In Your Details

**Copy this section and replace all [SQUARE_BRACKETS] with your information:**

```
[BOOK_TITLE]: 
[BOOK_SLUG]: 
[BOOK_CONCEPT]: 
[CORE_MESSAGE]: 
[TARGET_AUDIENCE]: 
[YOUR_EMAIL]: 
[AUTHOR_NAME]: 
[USERNAME]: 
[ARTWORK_DESCRIPTION]: 
[CHAPTER_1_FOCUS]: 
```

---

## 📝 Full Execution Prompt

**Once you've filled in the details above, copy and paste everything below into your AI assistant:**

---

When I say turn this into a book, I mean I need you to visually open up multiple tabs and execute the following workflow:

### STEP 1: CREATE ARTWORK

1. **Open Gemini tab**: Create a new tab and navigate to `https://gemini.google.com`
2. **Generate artwork**: In the Gemini prompt box, type:
   ```
   Create an image of [ARTWORK_DESCRIPTION]. The image should represent [CORE_MESSAGE]. Artistic style: hopeful, empowering, warm colors, digital illustration
   ```
3. **Wait for generation**: Let the image fully generate (wait 5 seconds after submitting)
4. **Keep tab open**: Leave this tab open - you'll need the link later

### STEP 2: CREATE GOOGLE DOC AND WRITE CONTENT

1. **Open Google Docs**: Create a new tab and navigate to `https://docs.new/`
2. **Update document title**: Click on "Untitled document" at the top and change it to: `[BOOK_TITLE] - Book Manuscript`
3. **Write the book concept**: Click in the document and type the following structure:

```
[BOOK_TITLE]

Why This Book?

[Write 3-4 paragraphs explaining why this book needs to exist, the problem it solves, and who it's for. Reference the TARGET_AUDIENCE and BOOK_CONCEPT]

The Mission

[Write 2-3 paragraphs about what you want readers to gain from this book]

What This Book Will Cover

1. [Chapter title based on CHAPTER_1_FOCUS]
2. [Chapter 2 title - logical progression]
3. [Chapter 3 title]
4. [Chapter 4 title]
5. [Chapter 5 title]
6. [Chapter 6 title]
7. [Chapter 7 title]
8. [Chapter 8 title - conclusion/next steps]

Who This Book Is For

- [TARGET_AUDIENCE - expand into 4-5 bullet points of specific reader types]

The Promise

[Write 2-3 paragraphs about what readers will be able to do/feel/achieve after reading]
```

4. **Write Chapter 1**: At the end of the document, add:

```


CHAPTER 1
[Chapter Title Based on CHAPTER_1_FOCUS]

[Write a compelling 2,000-2,500 word first chapter that:
- Opens with a specific moment or realization
- Introduces the core framework/concept
- Uses personal story or relatable scenario
- Ends with clear takeaway or transition to what's next]

---

[End of Chapter 1]
```

5. **Wait for auto-save**: Wait 2 seconds for Google Docs to save
6. **Keep tab open**: Leave this tab open - you'll need the link later

### STEP 3: FIND AND SET UP LEANPUB

1. **Open Leanpub**: Create a new tab and navigate to `https://leanpub.com/authors/create/book`
2. **Fill out book details**:
   - Title field: Type `[BOOK_TITLE]`
   - Book URL field: Clear the default and type `[BOOK_SLUG]`
   - Language: Keep as "English"
   - Writing Mode: Keep as "Plain Text Editor"

3. **Scroll down** to the "You" section (author details)

4. **Fill out author information**:
   - Name: `[AUTHOR_NAME]`
   - Username: `[USERNAME]`
   - Email: `[YOUR_EMAIL]`
   - Password: Generate a strong password like `[BookSlug]2025!Publish` (use the book slug + year + special char)

5. **Click "Next" button** to submit the form

6. **Wait for account creation**: The form will process and redirect (wait up to 10 seconds)

7. **Verify success**: You should land on a page showing the book editor with "Getting Started" template

### STEP 4: SEND EMAIL SUMMARY

1. **Open Gmail**: Create a new tab and navigate to `https://mail.google.com`
2. **Compose new email**: Click the "Compose" button or press `c` key
3. **Fill in email**:
   - To: `[YOUR_EMAIL]`
   - Subject: `✅ [BOOK_TITLE] - Book Project Complete - All Links & Credentials`
   
4. **Email body**:

```
Hi [AUTHOR_NAME],

I've completed the full setup for your "[BOOK_TITLE]" book project. Everything is ready to go!

✅ COMPLETED TASKS:

1. Created Book Artwork
   - Generated cover concept art using Gemini AI
   - Artwork URL: [Copy from Gemini tab URL]

2. Written Book Concept Document
   - Complete "Why This Book?" section
   - Mission statement and target audience
   - Full 8-chapter outline
   - Google Doc: [Copy from Google Docs tab URL]

3. Written Chapter 1 - [Chapter 1 title]
   - Full first chapter completed (~2,500 words)
   - Same Google Doc as above

4. Set Up Leanpub Publishing Platform
   - Account created with 80% royalty rate
   - Book listing live and ready to publish
   - Book URL: https://leanpub.com/[BOOK_SLUG]

🔑 LOGIN CREDENTIALS:

Website: https://leanpub.com/
Email: [YOUR_EMAIL]
Password: [The password you generated]
Author Dashboard: https://leanpub.com/author/book/[BOOK_SLUG]/write/Getting%20Started
Author Profile: https://leanpub.com/u/[USERNAME]

📚 ALL YOUR RESOURCES:

• Book Manuscript (Google Docs): [Google Doc URL]
• Cover Artwork (Gemini): [Gemini URL]
• Leanpub Dashboard: [Dashboard URL]

📝 NEXT STEPS:

1. Log in to Leanpub with the credentials above
2. Replace the "Getting Started" template with your content from the Google Doc
3. Use Markdown formatting (headings start with #, bold with **text**)
4. Click "Preview" to see how it looks as an ebook
5. Click "Publish" when ready to make it available

💰 LEANPUB DETAILS:

- 80% royalties on sales over $7.99
- Publish while still writing (readers get updates)
- Free to use
- No upfront costs

Your book project is now live and ready for you to continue writing!

Best,
Your AI Assistant
```

5. **Send the email**: Click "Send" button or press `Ctrl+Enter`

6. **Verify sent**: Wait for "Message sent" confirmation (2-3 seconds)

---

## 🛡️ Important Notes

**HUMAN-IN-THE-LOOP:**
If Google OAuth is NOT available on Leanpub (it uses manual form entry), the AI will:
1. Fill out all the fields with the information provided
2. Generate a secure password for you
3. Click submit to create the account
4. Email you the credentials

You do NOT need to manually enter anything - the AI handles the complete account creation.

**BOOK DETAILS FOR THIS RUN:**
- Book Title: [BOOK_TITLE]
- Book Concept: [BOOK_CONCEPT]
- Target Audience: [TARGET_AUDIENCE]
- Email: [YOUR_EMAIL]
- Author: [AUTHOR_NAME]

Execute the complete workflow above now.

---

## 📊 Example Usage

```
[BOOK_TITLE]: The Solopreneur's Survival Guide
[BOOK_SLUG]: solopreneur-survival
[BOOK_CONCEPT]: A practical roadmap for building a sustainable one-person business without burnout
[CORE_MESSAGE]: Balance, sustainability, and smart systems for solo entrepreneurs
[TARGET_AUDIENCE]: Freelancers and solo business owners struggling with overwhelm
[YOUR_EMAIL]: tasha@example.com
[AUTHOR_NAME]: Tasha Williams
[USERNAME]: tashawilliams
[ARTWORK_DESCRIPTION]: A confident solo entrepreneur working peacefully at a desk with organized systems around them - plants, a calm workspace, a sunset through the window, representing balance between work and life
[CHAPTER_1_FOCUS]: The breaking point moment when I realized my "successful" business was destroying my health and relationships - and what I did about it
```

---

## ✅ What You'll Get

✅ Professional AI-generated cover artwork  
✅ Complete book concept document (Why This Book, mission, audience, 8-chapter outline)  
✅ Full Chapter 1 written (~2,500 words)  
✅ Publishing platform account created with login credentials  
✅ Book listing live and ready to publish  
✅ Comprehensive email summary with all links  
✅ Ready to continue writing and publish  

**TIME TO COMPLETE:** ~5-10 minutes  
**COST:** $0 (all free platforms)

---

## 👤 Credits

Created by Loz Turner | [turnerworks](https://github.com/turnerworks)

Based on the successful workflow that created "UNBROKEN: Giving Children the Tools to Stand Strong"

---

## 📝 License

MIT License - Free to use, modify, and distribute
