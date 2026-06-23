## Step 2: Understanding HTML Structure and Common Tags

Now that you understand what HTML is, let's learn about the building blocks—the most common tags you'll encounter.

### 📖 Theory: HTML Tags and Document Structure

Every HTML page has a basic structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <!-- Metadata goes here -->
  </head>
  <body>
    <!-- Visible content goes here -->
  </body>
</html>
```

**Container Tags** (the main structure):
- `<html>` - The root element that wraps all content
- `<head>` - Contains metadata like page title and character encoding
- `<body>` - Contains all the visible content users see

**Content Tags** (common tags you'll see):
- `<h1>` through `<h6>` - Headings (h1 is the main heading, h6 is the smallest)
- `<p>` - Paragraph of text
- `<a>` - Link to another page (uses the `href` attribute)
- `<img>` - Image (uses the `src` attribute to specify the image file)
- `<button>` - A clickable button
- `<div>` - Generic container for grouping content

**Understanding Attributes**:

Tags can have attributes that provide additional information:

```html
<a href="https://github.com">Click here</a>
<img src="photo.jpg" alt="A beautiful sunset">
```

In these examples:
- `href` tells the link where to go
- `src` tells the image which file to display
- `alt` provides text to show if the image can't load

### ⌨️ Activity: Learn Tags Through Examples

1. Create an issue comment with your answers to these questions (use an AI assistant to help):

   **Question 1:** Look at this HTML:
   ```html
   <h1>My Blog</h1>
   <p>Welcome to my blog about web development.</p>
   ```
   What tag is used for the main heading? What tag is used for regular text?

   **Question 2:** What would happen if you used `<h6>` instead of `<h1>` for your main title? Ask an AI assistant: "In HTML, what's the visual difference between h1 and h6 tags?"

   **Question 3:** Look at this link tag:
   ```html
   <a href="https://skills.github.com">Learn GitHub Skills</a>
   ```
   What does the `href` attribute do? Try asking AI: "In this HTML link, what does href stand for and why is it important?"

2. Document your learning by commenting:
   - The three most common content tags and what they do
   - One example of an attribute and how it's used
  - Include this exact phrase anywhere in your comment: `I completed Step 2`

<details>
<summary>Having trouble? 🤷</summary><br/>

- Headings `<h1>` through `<h6>` are all used for different levels of headings on a page.
- The `href` attribute in a link specifies the URL (web address) where the link goes.
- If you're struggling with concepts, copy the example HTML into an AI assistant and ask: "Explain each tag in this HTML and what it does."

</details>
