## Step 4: Semantic HTML and Accessibility

In this step, you'll learn about semantic HTML and why accessibility matters.

### 📖 Theory: Semantic HTML

**What is Semantic HTML?**

Semantic HTML means using tags that describe their *purpose*, not just their appearance.

**Non-semantic vs. Semantic:**

```html
<!-- Non-semantic: Just a generic container -->
<div>
  <div>My Website</div>
  <div>
    <a href="/">Home</a>
    <a href="/about">About</a>
  </div>
</div>

<!-- Semantic: Tags describe their purpose -->
<header>
  <h1>My Website</h1>
  <nav>
    <a href="/">Home</a>
    <a href="/about">About</a>
  </nav>
</header>
```

**Common Semantic Tags:**
- `<header>` - Top of page or section
- `<nav>` - Navigation links
- `<main>` - Main content of the page
- `<article>` - A complete piece of content
- `<section>` - A thematic grouping of content
- `<footer>` - Bottom of page or section

**Why Does Semantic HTML Matter?**

1. **Accessibility**: Screen readers (used by people with visual impairments) understand semantic tags better
2. **SEO**: Search engines understand content better with semantic tags
3. **Readability**: Other developers can understand your code faster
4. **Maintainability**: Your code is easier to update and fix

### Accessibility Basics

Accessibility means making websites usable for everyone, including people with disabilities.

**Key Accessibility Practices:**

- **Alt text for images** - Describe what images show so screen readers can explain them:
  ```html
  <img src="sunset.jpg" alt="A beautiful sunset over the ocean">
  ```

- **Proper heading hierarchy** - Use h1, h2, h3 in order (don't skip levels):
  ```html
  <h1>Main Topic</h1>
  <h2>Subtopic</h2>
  <h3>Detail</h3>
  ```

- **Descriptive link text** - Tell users where a link goes:
  ```html
  <!-- Good -->
  <a href="/about">Learn about our team</a>
  
  <!-- Avoid -->
  <a href="/about">Click here</a>
  ```

### ⌨️ Activity: Improve HTML Accessibility

You'll review HTML with accessibility issues and ask AI to help improve it.

1. Review this HTML that has accessibility problems:

```html
<div>
  <div>My Portfolio</div>
  <div>
    <a href="/">Home</a>
    <a href="/projects">Projects</a>
  </div>
</div>

<img src="profile.jpg">

<div>
  <a href="/contact">click</a>
</div>
```

2. In an issue comment, answer these questions (use AI to help):
   - Ask an AI assistant: "What accessibility issues do you see in this HTML code?"
   - Ask: "How would you improve this HTML to be more accessible and semantic?"
   - Document at least 3 improvements the AI suggests

3. Explain in simple terms:
   - What is semantic HTML and why is it important?
   - What does alt text do for images?
   - Why should link text be descriptive?
  - Include this exact phrase anywhere in your comment: `I completed Step 4`

<details>
<summary>Having trouble? 🤷</summary><br/>

- Try copying the HTML into an AI assistant and asking: "What makes HTML code accessible to people with disabilities?"
- Look for non-semantic tags like lots of `<div>` that could be replaced with semantic tags
- Every image should have an `alt` attribute that describes what the image shows
- Semantic tags aren't just about accessibility—they make your code clearer for other developers too!

</details>
