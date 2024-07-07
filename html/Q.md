Meta tags in HTML provide metadata about the HTML document. They are typically used to specify page description, keywords, author, and other metadata. These tags are placed inside the `<head>` section of the HTML document. Here are some commonly used meta tags:

1. **Description**: Provides a brief description of the page content. This is often used by search engines in their results.
   ```html
   <meta name="description" content="A brief description of the page content">
   ```

2. **Keywords**: A list of keywords relevant to the content of the page. This tag is less important for search engines today but can still be useful.
   ```html
   <meta name="keywords" content="HTML, CSS, JavaScript, web development">
   ```

3. **Author**: Specifies the author of the document.
   ```html
   <meta name="author" content="John Doe">
   ```

4. **Viewport**: Controls the layout on mobile browsers.
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```

5. **Charset**: Specifies the character encoding for the HTML document.
   ```html
   <meta charset="UTF-8">
   ```

6. **Robots**: Instructs search engine crawlers about the page indexing and following links.
   ```html
   <meta name="robots" content="index, follow">
   ```

7. **Refresh**: Redirects the page after a specified number of seconds.
   ```html
   <meta http-equiv="refresh" content="30">
   ```

8. **Open Graph**: Used for social media sharing, primarily by Facebook.
   ```html
   <meta property="og:title" content="Title of the content">
   <meta property="og:description" content="Description of the content">
   <meta property="og:image" content="URL to image">
   <meta property="og:url" content="URL to content">
   ```

9. **Twitter Cards**: Used for Twitter sharing.
   ```html
   <meta name="twitter:card" content="summary">
   <meta name="twitter:title" content="Title of the content">
   <meta name="twitter:description" content="Description of the content">
   <meta name="twitter:image" content="URL to image">
   ```

10. **Content Security Policy (CSP)**: Helps prevent cross-site scripting (XSS) attacks and other cross-site injections.
    ```html
    <meta http-equiv="Content-Security-Policy" content="default-src 'self'; script-src 'self' example.com">
    ```

These meta tags help improve SEO, provide necessary information to browsers and crawlers, and enhance the user experience.
