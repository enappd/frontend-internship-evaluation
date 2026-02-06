### Assignment: The Waitlist UI

**Time Limit:** 2–3 Hours (Recommended)

**Objective:** Build and deploy a specific waitlist page using Next.js.

**Evaluation:**
We are looking for attention to detail from code to things you submit. The code is simple; following the specific constraints is the actual test.

#### 1. The Tech Stack

* **Framework:** Next.js (App Router preferred)
* **Styling:** Tailwind CSS
* **Hosting:** Netlify (Free Tier)

#### 2. The Application Requirements

You must build a single page with a centered card containing a form. simple UI is better.

**A. Visual Specs:**

* **Background:** Solid grey color (`#f3f4f6`).
* **Card:** White background, slight shadow, rounded corners.
* **Title:** "Internal Tools Access" (Font size 24px, Bold).
* **Button:** The submit button must specifically read: **"Request Access Token"**.
* **Form** : simple form input centered inside the card. No need of labels - you can use placeholders for explaining the field.

**B. Logic & Validation (Strict):**
*Do not* rely solely on HTML5 `required` attributes. You must handle state manually.

1. **Email Field:**
* **Constraint:** The email must **NOT** be a generic `@gmail.com` address. You must write logic to block Gmail addresses and show an error message. You can block top 5-10 most popular email domains.
* *Error Message:* "Business emails only."


2. **Reason Field:**
* A text area asking "Why do you need access?"
* **Constraint:** Must be **20 characters or more**. Show a character count or an error if it is too short.


3. **Success State:**
* Upon successful submission, the form must disappear and be replaced by the text: *"You have been added to the queue."* (No backend database needed, just handle the frontend state).


#### 3. The Deployment Pipeline

1. Initialize a **GitHub** repository.
2. Connect it to **Netlify** or **Vercel**.
3. Ensure that when you commit changes to your `main` branch, the live site updates automatically.

#### 4. The Documentation (Crucial)

You must include a `README.md` file in your repository. (this is will be evaluated)

* **Do not** copy-paste generic installation commands (e.g., `npm install`).
* **Do not** use AI to write this explanation. You can use AI for code but not README.md
* **Do:** Write in your own words (grammar does not matter) how you solved the specific constraints.
* *Example:* "I used regex to check for gmail," or "I used a simple if/else check on the string."
* Tell us one problem you faced while deploying or coding this and how you fixed it 


#### 5. Submission

Reply with:
1. The **GitHub Repository** link. 
Other things will be inside the README of same repo :
2. README.md 
3. The **Live Site URL** (Check that it works on mobile). ( add this link to README.md )

WHERE to submit :
- You can mail to abhishek@enappd.com with SUBJECT : INTERNSHIP CODE SUBMISSION 2026
- We just need your github repo link - make sure its public.

There is no deadline for this submission. 
Only thing is appications submitted first will be evaluated first - and have better chances.
