<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Communicate using Markdown

_Organize ideas and collaborate using Markdown, a lightweight language for text formatting._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Step 5: Merge your pull request

_Great job adding a task list to the file :heart:_

You can now [merge](https://docs.github.com/get-started/quickstart/github-glossary#merge) your work!

### :keyboard: Activity: Complete the course

Since we're working locally, let's commit all your changes and merge them to complete the course:

1. Commit all your Markdown changes to the `index.md` file
2. Switch back to the main branch
3. Merge your `start-markdown` branch

**What you've accomplished:**
- ✅ Added headers (H1-H6)
- ✅ Included an image with alt text
- ✅ Added code examples (inline and blocks)
- ✅ Created a task list with checkboxes

Great work learning Markdown! 🎉

## Step 4: Make a task list

_Great job adding a code example to the file :partying_face:_

**What is a _task list_?** A task list creates checkboxes to check off. They're very useful for tracking issues and pull requests. If you include a task list in the body of an issue or pull request, you'll see a progress indicator in your issue list. The syntax for task lists is very specific. Be sure to include the spaces where required, or else they won't render.

### Example

```
- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete
```

#### How it looks

- [x] List syntax is required
- [x] This item is complete
- [ ] This item is not complete

### :keyboard: Activity: Add a task list

1. Edit the `index.md` file in this repository.
2. Use Markdown to create a task list. Here is an example:

   ```md
   - [ ] Turn on GitHub Pages
   - [ ] Outline my portfolio
   - [ ] Introduce myself to the world
   ```

   Remember, a task list starts with the syntax `- [ ]` and then the task list item. The formatting is specific!

3. Use the **Preview** tab to check your Markdown formatting.
4. Commit the changes to continue to the next step.

**Task List Syntax:**
- `- [x] Completed task` (checked)
- `- [ ] Incomplete task` (unchecked)

## Step 2: Add an image

_Great job adding headers to the file :sparkles:_

Let's add an image. Include descriptive text in the square brackets. This text is read aloud for people using screen readers. It's also shown at times when your image doesn't display, such as when there's a poor connection. You can see the syntax for images below:

### Example

```md
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```

#### How it looks

<img alt="Image of Yaktocat" src=https://octodx.github.com/images/yaktocat.png width=400>

### :keyboard: Activity: Adding an image

1. Edit the `index.md` file in this repository.
2. In the file, add the correct Markdown for your image of choice. Don't forget to include alt-text!
3. Use the **Preview** tab to check your Markdown formatting.
4. Commit your changes to continue to the next step.

**Image Syntax:**
```md
![Alt text](image-url)
```

## Step 1: Add headers

_Welcome to "Communicate using Markdown"! :wave:_

**What is _Markdown_?** Markdown is a [lightweight syntax](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax) for communicating on GitHub. You can format text to add a heading, lists, **bold**, _italics_, tables, and many other stylings. You can use Markdown in most places around GitHub:

- Comments on [issues](https://docs.github.com/issues/tracking-your-work-with-issues/about-issues), [pull requests](https://docs.github.com/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests), and [discussions](https://docs.github.com/discussions/collaborating-with-your-community-using-discussions/about-discussions)
- Files with the `.md` or `.markdown` extension
- Sharing snippets of text in [Gists](https://docs.github.com/github/writing-on-github/editing-and-sharing-content-with-gists/creating-gists)

**What is a _header_?** A header is a larger bit of text at the beginning of a section. There are six sizes.

### Example

```md
# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest
```

#### How it looks

# This is an `<h1>` header, which is the largest

## This is an `<h2>` header

###### This is an `<h6>` header, which is the smallest

### :keyboard: Activity: Edit your file with headers

1. Open the `index.md` file in this repository.
2. Add a `#`, followed by a **space**, before any content you like to make it an H1 Header. You can add more headers, using one to six `#` characters followed by a **space**.
3. Preview your changes to see how they look.
4. Commit your changes to continue to the next step.

## Welcome

GitHub is about more than code. It’s a platform for software collaboration, and Markdown is one of the most important ways developers can make their communication clear and organized in issues and pull requests. This course will walk you through creating and using headings more effectively, organizing thoughts in bulleted lists, and showing how much work you’ve completed with checklists. You can even use Markdown to add some depth to your work with the help of emoji, images, and links.

- **Who is this for**: New developers, new GitHub users, and students.
- **What you'll learn**: Use Markdown to add lists, images, and links in a comment or text file.
- **What you'll build**: We'll update a plain text file and add Markdown formatting, and you can use this file to start your own GitHub Pages site.
- **Prerequisites**: In this course you will work with pull requests as well as edit files. If these things aren't familiar to you, we recommend you take the [Introduction to GitHub](https://github.com/skills/introduction-to-github) course, first!
- **How long**: This course takes less than one hour to complete.

In this course, you will:

1. Add headers
2. Add an image
3. Add a code example
4. Make a task list
5. Merge your pull request

### How to start this course

1. Scroll to the top of the page and click the down arrow next to the Fork button. Then click 'Create a new fork' to fork this repository.
2. Right-click **Start course** and open the link in a new tab.

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'communicate-using-markdown',
  owner: '@me',
  name: 'skills-communicate-using-markdown',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=communicate-using-markdown&owner=%40me&name=skills-communicate-using-markdown&description=My+clone+repository&visibility=public)

3. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
4. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/communicate-using-markdown) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
