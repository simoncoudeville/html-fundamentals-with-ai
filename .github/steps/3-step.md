## Step 3: Reading HTML and Prompting AI Effectively

In this step, you'll practice reading HTML code like a document and learn how to write effective prompts for AI.

### 📖 Theory: Reading and Prompting

**How to Read HTML:**

Reading HTML is like reading a structured document:

1. **Look at indentation** - Indentation shows which tags are inside others (nesting)
2. **Follow opening and closing tags** - Each opening tag has a closing tag
3. **Understand the hierarchy** - Tags can contain other tags

Example:
```html
<div>
  <h2>My Section</h2>
  <p>This paragraph is inside the div.</p>
  <a href="/">Home</a>
</div>
```

Here, the `<h2>`, `<p>`, and `<a>` are all *nested* inside the `<div>`.

**Writing Effective Prompts for AI:**

Good prompts get better results. Follow this structure:

1. **Be specific** - Describe exactly what you want
2. **Give context** - Explain the situation or purpose
3. **Ask for explanation** - Request that AI explain the code, not just generate it
4. **Iterate** - If the result isn't what you expected, ask follow-up questions

**Good prompt examples:**
- "Create an HTML page for a local coffee shop. Include the shop name as a heading, a menu section with at least 3 items, and a contact link."
- "Explain what each line of this HTML does" (then paste code)
- "How would you improve this HTML to be more accessible?"

### ⌨️ Activity: Write and Test a Prompt

1. Write a prompt for AI that describes a webpage you'd like to create. Your prompt should:
   - Describe what the page is about
   - Mention at least 3 content elements (heading, paragraphs, links, etc.)
   - Ask AI to explain the code

   Example: "Create a simple resume in HTML that includes my name as a heading, a summary paragraph about me, and a list of my skills. Please also explain which tags you used and why."

2. Share your prompt in an issue comment, then ask an AI assistant to generate HTML based on it.

3. Review the AI-generated HTML and answer these questions in your issue comment:
   - Can you identify at least 3 tags in the generated HTML?
   - What do you think the `<div>` tags are doing?
   - Ask the AI: "Why did you use semantic tags like `<main>` or `<section>` in this code?" and document their response

4. Take note of what worked well in your prompt and what you might change next time.

5. In your issue comment, include this exact phrase to complete the step: `I completed Step 3`

<details>
<summary>Having trouble? 🤷</summary><br/>

- If AI generates code that seems confusing, ask it to explain each section step by step
- A vague prompt like "make a webpage" often gives vague results. Be specific!
- It's okay if the first prompt doesn't give exactly what you wanted—that's when you ask follow-up questions
- Try copying the HTML into a new chat and asking: "Can you walk me through what this code does line by line?"

</details>
