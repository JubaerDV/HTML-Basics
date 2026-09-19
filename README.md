🗺️ HTML Learning Roadmap
🟢 Level 1 — HTML Basics
HTML কী?
HTML Document Structure
Tags
Elements
Attributes
<head> / <body>
Headings — <h1> to <h6>
Paragraph — <p>
Line Break — <br>
Horizontal Line — <hr>

1. What is HTML?
English

HTML stands for HyperText Markup Language.

HTML is the standard markup language used to create the structure of web pages.

HTML can be used to create:

Headings
Paragraphs
Images
Links
Lists
Tables
Forms
Buttons

HTML is not a programming language. It is a markup language.

বাংলা

HTML-এর পূর্ণরূপ হলো HyperText Markup Language।

HTML ব্যবহার করে একটি website-এর structure বা কাঠামো তৈরি করা হয়।

যেমন:

Heading তৈরি করা
Paragraph লেখা
Image দেখানো
Link তৈরি করা
List তৈরি করা
Table তৈরি করা
Form তৈরি করা
Button তৈরি করা

সহজভাবে:

HTML = Website-এর Structure

Example
<h1>Hello World</h1>
<p>This is my first website.</p>

এখানে <h1> দিয়ে heading এবং <p> দিয়ে paragraph তৈরি করা হয়েছে।

2. HTML Document Structure
English

An HTML document has a basic structure that tells the browser how to understand the webpage.

A standard HTML document looks like this:

<!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
</head>

<body>

    <h1>Hello World</h1>
    <p>This is my website.</p>

</body>
</html>
বাংলা

একটি HTML file-এর একটি নির্দিষ্ট basic structure থাকে।

সাধারণত HTML document-এর মধ্যে থাকে:

DOCTYPE
   ↓
HTML
   ↓
HEAD
   ↓
BODY
Structure বুঝে নাও
<!DOCTYPE html>

<html>

<head>
    ...
</head>

<body>
    ...
</body>

</html>
<!DOCTYPE html> → Browser-কে HTML version সম্পর্কে জানায়
<html> → পুরো HTML document
<head> → Website-এর information/settings
<body> → Website-এ যা দেখা যায়
3. DOCTYPE
English

<!DOCTYPE html> tells the browser that the document is written using HTML5.

It should normally be the first line of an HTML document.

বাংলা

<!DOCTYPE html> browser-কে বলে যে আমরা HTML5 ব্যবহার করছি।

এটি HTML file-এর প্রথম লাইনে লেখা হয়।

Example
<!DOCTYPE html>
<html>
<head>
    <title>My Page</title>
</head>

<body>
    <h1>Hello</h1>
</body>
</html>
মনে রাখবে
<!DOCTYPE html>

এটা সাধারণত HTML document-এর প্রথম লাইন।

4. HTML Tags
English

HTML tags are special keywords written inside angle brackets < >.

Example:

<h1>
<p>
<body>

Most HTML tags have an opening tag and a closing tag.

<p>Hello</p>

Here:

<p>       → Opening tag
Hello     → Content
</p>      → Closing tag
বাংলা

HTML tag হলো এমন কিছু keyword যেগুলো < > এর মধ্যে লেখা হয়।

যেমন:

<h1>
<p>
<body>

অনেক HTML tag-এর opening এবং closing tag থাকে।

Example
<p>Hello World</p>

এখানে:

<p> → Opening tag
Hello World → Content
</p> → Closing tag
5. HTML Elements
English

An HTML element usually consists of:

Opening Tag + Content + Closing Tag

Example:

<p>Hello World</p>

The complete thing is called an HTML element.

বাংলা

HTML element সাধারণত তৈরি হয়:

Opening Tag
+
Content
+
Closing Tag

উদাহরণ:

<p>Hello World</p>

পুরো অংশটিই একটি HTML element।

আরেকটি Example
<h1>My Website</h1>

এটি একটি heading element।

<p>I am learning HTML.</p>

এটি একটি paragraph element।

সহজে মনে রাখো

Tag:

<p>

Element:

<p>Hello</p>
6. HTML Attributes
English

Attributes provide additional information about an HTML element.

Attributes are written inside the opening tag.

Example:

<a href="https://example.com">Visit Website</a>

Here:

href = attribute
"https://example.com" = attribute value
বাংলা

Attribute হলো HTML element সম্পর্কে অতিরিক্ত information দেওয়ার জন্য ব্যবহার করা হয়।

Attribute সাধারণত opening tag-এর মধ্যে লেখা হয়।

Example
<a href="https://example.com">Visit Website</a>

এখানে:

href="https://example.com"

পুরোটা হলো attribute।

href → Attribute name
"https://example.com" → Attribute value
Image Example
<img src="photo.jpg" alt="My Photo">

এখানে:

src → Image-এর location
alt → Image-এর alternative text
7. Head
English

The <head> element contains information about the webpage that is generally not displayed directly on the webpage.

It can contain:

<title>
<meta>
<link>
CSS references
Other settings
বাংলা

<head> অংশে webpage-এর বিভিন্ন information এবং settings থাকে।

এগুলোর বেশিরভাগ সরাসরি webpage-এর ভিতরে দেখা যায় না।

Example:

<head>
    <title>My Website</title>
</head>

এখানে <title> browser-এর tab-এ website-এর নাম দেখায়।

Example
<!DOCTYPE html>
<html>

<head>
    <title>My First Website</title>
</head>

<body>
    <h1>Hello World</h1>
</body>

</html>

Browser-এর tab-এ দেখা যাবে:

My First Website

8. Body
English

The <body> element contains the visible content of a webpage.

For example:

Headings
Paragraphs
Images
Links
Lists
Tables
Forms
Buttons
বাংলা

<body> এর ভিতরে webpage-এর যে content user দেখতে পায়, সেগুলো রাখা হয়।

যেমন:

<body>

    <h1>My Website</h1>

    <p>Welcome to my website.</p>

</body>

Browser-এ দেখা যাবে:

My Website

Welcome to my website.

সহজভাবে
<head>
    Website-এর information/settings
</head>

<body>
    Website-এর visible content
</body>
9. Headings
English

HTML provides six levels of headings:

<h1>
<h2>
<h3>
<h4>
<h5>
<h6>

<h1> is the highest-level/main heading, while <h6> is the lowest-level heading.

বাংলা

HTML-এ মোট ৬ ধরনের heading আছে।

<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
Example
<h1>My Website</h1>
<h2>About Me</h2>
<h3>My Skills</h3>
<h4>HTML</h4>
<h5>Basic HTML</h5>
<h6>Introduction</h6>
গুরুত্বপূর্ণ

সাধারণভাবে page-এর প্রধান heading হিসেবে <h1> ব্যবহার করা হয়। তারপর content-এর hierarchy অনুযায়ী <h2>, <h3> ইত্যাদি ব্যবহার করা হয়।

10. Paragraph
English

The <p> tag is used to create a paragraph.

Example:

<p>This is a paragraph.</p>
বাংলা

<p> tag ব্যবহার করে paragraph বা অনুচ্ছেদ লেখা হয়।

Example
<p>
    My name is Jubayer.
    I am learning HTML.
</p>

আরেকটি paragraph:

<p>I want to become a Full Stack Developer.</p>

প্রতিটি আলাদা paragraph-এর জন্য <p> ব্যবহার করা যায়।

11. Line Break
English

The <br> tag is used to create a line break.

It moves the following content to a new line.

Example:

Hello<br>
World

Output:

Hello
World
বাংলা

<br> tag ব্যবহার করে একটি line থেকে পরের line-এ যাওয়া যায়।

Example
<p>
    My name is Jubayer.<br>
    I am learning HTML.<br>
    I love coding.
</p>

Output:

My name is Jubayer.
I am learning HTML.
I love coding.
মনে রাখবে

<br> এর closing tag নেই।

❌ ভুল:

<br></br>

সাধারণ HTML-এ:

<br>

ব্যবহার করলেই হয়।

12. Horizontal Rule
English

The <hr> tag creates a horizontal line across the page.

It is commonly used to separate different sections of content.

বাংলা

<hr> tag webpage-এ একটি horizontal line তৈরি করে।

এটি সাধারণত দুইটি section বা content আলাদা করতে ব্যবহার করা হয়।

Example
<h1>About Me</h1>

<p>I am learning HTML.</p>

<hr>

<h2>My Skills</h2>

<p>HTML, CSS and JavaScript</p>

এখানে About Me এবং My Skills section-এর মধ্যে একটি horizontal line তৈরি হবে।

<hr>-এরও closing tag লাগে না।

🧠 সবগুলো একসাথে

এখন Level 1-এর সব topic একসাথে একটি ছোট HTML file-এ দেখো:

<!DOCTYPE html>

<html>

<head>
    <title>My First HTML Page</title>
</head>

<body>

    <h1>My First Website</h1>

    <h2>About Me</h2>

    <p>
        My name is Jubayer.
        I am learning HTML.
    </p>

    <hr>

    <h2>My Goal</h2>

    <p>
        I want to become a Full Stack Developer.
    </p>

    <h3>My Learning</h3>

    <p>
        I am learning HTML.<br>
        Next I will learn CSS.<br>
        Then I will learn JavaScript.
    </p>

</body>

</html>
🔍 এই code-এর structure
<!DOCTYPE html>
       ↓
    <html>
       ↓
     <head>
       ↓
     <title>
       ↓
     </head>
       ↓
     <body>
       ↓
   ┌───────────────┐
   │     <h1>      │
   │     <h2>      │
   │     <p>       │
   │     <hr>      │
   │     <h3>      │
   │     <br>      │
   └───────────────┘
       ↓
     </body>
       ↓
    </html>
⭐ Level 1-এর সবচেয়ে গুরুত্বপূর্ণ জিনিস
Topic	কাজ
<!DOCTYPE html>	HTML5 document ঘোষণা করে
<html>	পুরো HTML document-এর root
<head>	Page-এর information/settings
<body>	Visible webpage content
<h1>–<h6>	Heading তৈরি করে
<p>	Paragraph তৈরি করে
<br>	নতুন line তৈরি করে
<hr>	Horizontal line তৈরি করে
Tag	HTML markup
Element	Opening tag + content + closing tag
Attribute	Element-এর অতিরিক্ত information
