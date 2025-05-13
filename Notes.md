# Section-01 : Frontend Web Development

## What is Internet?

- The Internet is a vast network of wires (and wireless systems) that connect different computers around the world.

- These computers can be located anywhere (even in different cities or countries) and can communicate and transfer data with one another.

- Servers are special computers that store and serve the data and files needed to access and interact with websites.

- Any computer that a user uses to access the Internet is called a client.

## How internet works?

- You type a URL (like www.google.com) in your browser.

- The browser sends that request to your ISP (Internet Service Provider).

- The ISP forwards the request to a DNS (Domain Name System) server.

- DNS has IP (Internet Protocol) adddress of all websites in the database, so when ISP sends the request, DNS tries to find exact IP address in the database of the website that are you tring to access.

- Every single computer(device) that's connected to the internet has an unique IP address (like postal code for the computer).

- Once the DNS server finds that IP address, it will send it back to your browser through the ISP, then browser can make a direct request to that address.

- And then server receives the request and responds by sending the necessary files back to your browser.

- You can look up the IP address of the any webpage/website using [www.nslookup.io](https://www.nslookup.io/)

- Explore how global Internet infrastructure works at [submarinecablemap.com](https://www.submarinecablemap.com/)

## How Do websites actually work?

- A client sends a request to a server, and the server responds by sending back files.

  These files typically consist of three types of files HTML, CSS, JS.:

  HTML: Provides the structure and content of the web page.

  CSS: Handles the styling and layout of the web page.

  JavaScript (JS): Adds interactivity and dynamic functionality to the website.

# Section-02 : Introduction to HTML

## What is HTML?

- HTML stands for HyperText Markup Language.

- **HyperText :** it refers to the pieces of text which can link to other documents in the website.
- So these pieces of text are hypertext or hyperlinks

  ```html
  <a href="https://www.example.com">Visit Example</a>
  ```

- **Markup Language :** is a way of annotating content with tags that describe the structure and presentation of text.

  ```html
  <p>This is a paragraph of text.</p>
  ```

## Heading Element:

    ```html
        <h1>Hello World</h1>
    ```

## \<Tag> vs. Element

- Anything that's inside an angle bracket, we call these "angle brackets", is a tag.

  ```html
  <h1> -> opening tag
  </h1> -> closing tag
  ```

- Opening tag and closing tag along with the content is called the element.
  ```html
  <h1>Hello World</h1>
  ```

## Headings in HTML

- There are six level of section headings are present in HTML.
- `<h1>` is the highest section level and `<h6>` is the lowest.
- By default all headings are block level elements (starting on a new line and taking up the full width available in their containing block).
- Do not use heading elements to resize text. Instead, use the CSS `font-size` property.

- Do not skip heading levels: always start from `<h1>`, followed by `<h2>` and so on.

- Heading information can be used by search engines for SEO purpose.


  ```html
  <h1>Hello World</h1>
  <h2>Hello World</h2>
  <h3>Hello World</h3>
  <h4>Hello World</h4>
  <h5>Hello World</h5>
  <h6>Hello World</h6>
  ```

- In a webpage try to use only one `<h1>` for the main section. A page should generally have a single `<h1>` element that describes the content of the page (similar to the document's `<title>` element).

- The HTML standard specifies that \<h1> elements in a \<section>, \<article>, \<aside>, or \<nav> element should render as an \<h2> (smaller font-size with an adjusted margin-block), or as an \<h3> if nested another level, and so on.

- For more details about Headings [click here](https://developer.mozilla.org/en-US/docs/Web/HTML/Reference/Elements/Heading_Elements)

## Paragraph element

- Paragraph is used for formatting and putting text on the webpage. We use `<p>` tag to write a paragraph on the webpage.
- It is a block level element, always starts with new line and take full width.

  ```html
  <p>This is sample txt.</p>
  ```

- Lorem Ipsum website [Lorem Ipsum](https://www.lipsum.com)
- Bacon Ipsum website [Bacon Ipsum](https://baconipsum.com)
- Bro Ipsum website [bro Ipsum](https://broipsum.com)

## HTML Void elements

- A void element is an element which do not have the content. and also don't have the closing tag.

  ```html
  <hr />
  <br />
  <img />
  <!-- These are void / empty elements -->
  <!-- In void elements you can ignore the / but use for good practice -->
  ```

- Diffchecker website [Diffchecker](https://www.diffchecker.com/)
