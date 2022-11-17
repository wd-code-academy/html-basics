# HTML Fundamentals and Semantics

[HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) or Hyper Text Markup Language is the foundation for _every_ website and application on the World Wide Web. Before the YouTubes and the Twitters, the Web was originally created to send nerdy research documents to other nerds across the country. The keyword being "document"; as in something similar to a Word doc. This is an important part of history to remember, because websites are still built with this purpose in mind.

As part of the foundation of your website, HTML also provides _meaning_ to your content. Without HTML, the content on your webpage will have no meaning in the eyes of search engines and screen readers. A well structured HTML file should resemble a Word Doc, when all of the styles and behavior are stripped.

## Assignment
You are a content manager at a popular web blog. The head writer has given two `.txt` text files full of information about the Marvel Cinematic Universe (MCU) and it's comic tie-ins. Your job is to review the content provided to you and (to the best of your ability) annotate the content with HTML to provide meaning. This content will later be published online via the blog website.

With that in mind, it is incredibly important to use the correct HTML tags at the right time. Not only is it vital for your SEO efforts (search engine optimization) but it's important for screen readers to consume the content. Comics and movies are for everyone. Everyone should be able to enjoy these stories regardless of any difficulties they may face.

## Requirements
- Create an `index.html` file as your "homepage"
- Every page should have the "HTML5 DOCTYPE"
- Every page must contain a `title`, `description`, `author`, and `keywords`
- Every page must have _relative_ links to other pages in order to navigate between them
- One absolute link to an external page (can be on any `.html` file)
- Links to email addresses where applicable

Between the three `html` pages, your project must contain following HTML tags listed below, _at least once_:
- `div`
- `section`
- `article`
- `aside`
- `header`
- `footer`
- `h1` to `h6`
- `blockquote`
- `p` (paragraph)
- `a` (anchor, hyperlink)
- `b` (bold)
- `q` (quotation)
- `i` (italic)
- `em` (emphasis)
- `strong`
- `abbr` (abbreviation)
- `ul`
- `li`
- `ol`
- `table` (`tr`, `td`, `th`, etc)

The `index.html` file will act as your homepage. This homepage will have some general information that you provide as well as links to `movies.html` and `comics.html`.

## Project Evaluation
When complete, your project should _at least_ have the following files:
- `index.html`
- `movies.html`
- `comics.html`

The instructor will pull down your code and checkout to the `development` branch. From there, they will test all files in a web browser and click on any links to make sure they work. After an intial run through, the instructor will look through your code and provide feedback via the Pull Request (PR) that you submit through Canvas. The instructor will run your code through the W3C HTML Validator (see below) to make sure that there are no errors with the code provided.

Points will be deducted if you...
- Use tags incorrectly
- Any of the requirements are missing
- Commit to the `main` branch
- Links don't work
- Errors with W3C validation

It's also important to note that you will have to use some of these tags multiple times. Points will be deducted if you fail to annotate content even if requirements are technically met.

## W3C Validation
Mastering the fundamentals of HTML and understanding the semantics is incredibly important moving forward. Be sure to regularly validate your HTML files using the W3C Validation Service. This will ensure that your HTML code is technically and semantically [valid](https://validator.w3.org/docs/help.html#validation_basics).

The W3C Validator might also provide clues if you are stuck.

## Resources
- [W3C Validator](https://validator.w3.org/)
- [Mozilla Developer Docs](https://developer.mozilla.org/en-US/docs/Learn/HTML)
- [Git Basics](https://rogerdudler.github.io/git-guide/)
