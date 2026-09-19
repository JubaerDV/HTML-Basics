

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F172A,50:2563EB,100:06B6D4&height=230&section=header&text=Basic%20HTML%20Learn&fontSize=42&fontColor=FF0000&animation=fadeIn&fontAlignY=38&desc=Hyper%20Text%20Markup%20%7C%20HTML%20Learning&Language=60&descSize=18" width="100%"/>

<br/>


<a href="https://git.io/typing-svg">
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=2563EB&center=true&vCenter=true&width=750&lines=Welcome+to+Level+1+Basic+HTML+%F0%9F%91%8B;Hypertext+Markup+Language+%F0%9F%92%BB;My+HTML+Learning+Journey+%F0%9F%8E%A8;Building+Modern+Web+Experiences+%F0%9F%9A%80;Learning+%7C+Building+%7C+Improving+%E2%9C%A8" alt="Typing SVG"/>
</a>


<br/><br/>

<img src="https://komarev.com/ghpvc/?username=JubaerDV&label=PROFILE%20VIEWS&color=2563EB&style=for-the-badge" alt="Profile Views"/>

</div>

---
# 🟢 Level 1 — HTML Basics

> 🚀 **My HTML Learning Journey — From Beginner to Web Developer**

Welcome to **Level 1 of my HTML Learning Journey**.
In this level, I am learning the fundamental concepts of HTML and understanding how a webpage is structured.

---

## 📚 Topics Covered

### 1️⃣ What is HTML?

**English:**
HTML stands for **HyperText Markup Language**. It is the standard markup language used to create the **structure of web pages**.

HTML can be used to create:

* Headings
* Paragraphs
* Images
* Links
* Lists
* Tables
* Forms
* Buttons

HTML is **not a programming language**. It is a **markup language**.

**বাংলা:**
HTML-এর পূর্ণরূপ হলো **HyperText Markup Language**।

HTML ব্যবহার করে একটি website-এর **structure বা কাঠামো** তৈরি করা হয়।

সহজভাবে:

> **HTML = Website-এর Structure**

### Example

```html
<h1>Hello World</h1>
<p>This is my first website.</p>
```

---

## 2️⃣ HTML Document Structure

**English:**
An HTML document has a basic structure that tells the browser how to understand and display the webpage.

### Basic Structure

```html
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
```

**বাংলা:**
একটি HTML document-এর একটি নির্দিষ্ট basic structure থাকে।

```text
DOCTYPE
   ↓
HTML
   ↓
HEAD
   ↓
BODY
```

* `<!DOCTYPE html>` → Browser-কে HTML5 document সম্পর্কে জানায়
* `<html>` → পুরো HTML document-এর root element
* `<head>` → Website-এর information এবং settings
* `<body>` → Website-এর visible content

---

## 3️⃣ DOCTYPE

**English:**
`<!DOCTYPE html>` tells the browser that the document uses **HTML5**.

It is normally written as the **first line** of an HTML document.

**বাংলা:**
`<!DOCTYPE html>` browser-কে জানায় যে আমরা **HTML5** ব্যবহার করছি।

এটি HTML file-এর সাধারণত **প্রথম লাইনে** লেখা হয়।

### Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Page</title>
</head>

<body>
    <h1>Hello</h1>
</body>
</html>
```

---

## 4️⃣ HTML Tags

**English:**
HTML tags are special keywords written inside **angle brackets `< >`**.

Examples:

```html
<h1>
<p>
<body>
```

Most HTML tags have an opening tag and a closing tag.

```html
<p>Hello World</p>
```

Here:

```text
<p>       → Opening Tag
Hello     → Content
</p>      → Closing Tag
```

**বাংলা:**
HTML tag হলো এমন keyword যা `< >` এর মধ্যে লেখা হয়।

উদাহরণ:

```html
<h1>
<p>
<body>
```

অনেক HTML tag-এর opening এবং closing tag থাকে।

---

## 5️⃣ HTML Elements

**English:**
An HTML element usually consists of:

```text
Opening Tag + Content + Closing Tag
```

Example:

```html
<p>Hello World</p>
```

The complete structure is called an **HTML element**.

**বাংলা:**
HTML element সাধারণত তৈরি হয়:

```text
Opening Tag
+
Content
+
Closing Tag
```

### Example

```html
<h1>My Website</h1>
```

এটি একটি **heading element**।

```html
<p>I am learning HTML.</p>
```

এটি একটি **paragraph element**।

### Remember

**Tag:**

```html
<p>
```

**Element:**

```html
<p>Hello</p>
```

---

## 6️⃣ HTML Attributes

**English:**
Attributes provide **additional information** about an HTML element.

Attributes are written inside the **opening tag**.

### Example

```html
<a href="https://example.com">Visit Website</a>
```

Here:

```text
href = Attribute Name
"https://example.com" = Attribute Value
```

**বাংলা:**
Attribute ব্যবহার করে একটি HTML element সম্পর্কে **অতিরিক্ত information** দেওয়া হয়।

Attribute সাধারণত **opening tag-এর ভিতরে** লেখা হয়।

### Image Example

```html
<img src="photo.jpg" alt="My Photo">
```

* `src` → Image-এর location
* `alt` → Image-এর alternative text

---

## 7️⃣ Head

**English:**
The `<head>` element contains information and settings about the webpage.

It can contain:

* `<title>`
* `<meta>`
* `<link>`
* CSS references
* Other settings

**বাংলা:**
`<head>` অংশে webpage-এর বিভিন্ন **information এবং settings** থাকে।

এগুলো সাধারণত webpage-এর মূল content হিসেবে সরাসরি দেখা যায় না।

### Example

```html
<head>
    <title>My Website</title>
</head>
```

`<title>` browser tab-এ website-এর নাম দেখায়।

---

## 8️⃣ Body

**English:**
The `<body>` element contains the **visible content** of a webpage.

It can contain:

* Headings
* Paragraphs
* Images
* Links
* Lists
* Tables
* Forms
* Buttons

**বাংলা:**
`<body>` এর ভিতরে webpage-এর **যে content user দেখতে পায়**, সেগুলো রাখা হয়।

### Example

```html
<body>

    <h1>My Website</h1>

    <p>Welcome to my website.</p>

</body>
```

---

## 9️⃣ Headings

**English:**
HTML provides **six levels of headings**:

```html
<h1>
<h2>
<h3>
<h4>
<h5>
<h6>
```

`<h1>` is the main/highest-level heading, while `<h6>` is the lowest-level heading.

**বাংলা:**
HTML-এ মোট **৬ ধরনের heading** রয়েছে।

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

### Example

```html
<h1>My Website</h1>
<h2>About Me</h2>
<h3>My Skills</h3>
<h4>HTML</h4>
<h5>Basic HTML</h5>
<h6>Introduction</h6>
```

---

## 🔟 Paragraph

**English:**
The `<p>` tag is used to create a **paragraph**.

### Example

```html
<p>This is a paragraph.</p>
```

**বাংলা:**
`<p>` tag ব্যবহার করে **paragraph বা অনুচ্ছেদ** লেখা হয়।

### Example

```html
<p>
    My name is Jubayer.
    I am learning HTML.
</p>
```

আরেকটি paragraph:

```html
<p>I want to become a Full Stack Developer.</p>
```

---

## 1️⃣1️⃣ Line Break

**English:**
The `<br>` tag is used to create a **line break**.

### Example

```html
Hello<br>
World
```

Output:

```text
Hello
World
```

**বাংলা:**
`<br>` tag ব্যবহার করে একটি line থেকে পরের line-এ যাওয়া যায়।

### Example

```html
<p>
    My name is Jubayer.<br>
    I am learning HTML.<br>
    I love coding.
</p>
```

Output:

```text
My name is Jubayer.
I am learning HTML.
I love coding.
```

> 💡 `<br>` একটি void element, তাই এর closing tag লাগে না।

---

## 1️⃣2️⃣ Horizontal Rule

**English:**
The `<hr>` tag creates a **horizontal line** and is commonly used to separate sections of content.

### Example

```html
<h1>About Me</h1>

<p>I am learning HTML.</p>

<hr>

<h2>My Skills</h2>

<p>HTML, CSS and JavaScript</p>
```

**বাংলা:**
`<hr>` tag webpage-এ একটি **horizontal line** তৈরি করে।

এটি সাধারণত বিভিন্ন section বা content আলাদা করতে ব্যবহার করা হয়।

> 💡 `<hr>` একটি void element, তাই এর closing tag লাগে না।

---

# 🧩 Complete Level 1 Example

```html
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
```

---

# 🧠 Quick Revision

| Topic             | Purpose                            |
| ----------------- | ---------------------------------- |
| `<!DOCTYPE html>` | Declares an HTML5 document         |
| `<html>`          | Root of the HTML document          |
| `<head>`          | Contains page information/settings |
| `<body>`          | Contains visible webpage content   |
| `<h1>`–`<h6>`     | Creates headings                   |
| `<p>`             | Creates paragraphs                 |
| `<br>`            | Creates a line break               |
| `<hr>`            | Creates a horizontal rule          |
| Tag               | HTML markup inside `< >`           |
| Element           | Complete HTML structure            |
| Attribute         | Provides additional information    |

---

# 🎯 What I Learned in Level 1

Through this level, I learned:

* ✅ What HTML is
* ✅ HTML document structure
* ✅ DOCTYPE
* ✅ HTML Tags
* ✅ HTML Elements
* ✅ HTML Attributes
* ✅ Head
* ✅ Body
* ✅ Headings
* ✅ Paragraphs
* ✅ Line Breaks
* ✅ Horizontal Rules

---

## 🚀 Next Level

**Level 2 — HTML Text Formatting**

Coming next:

```text
<b>
<strong>
<i>
<em>
<mark>
<small>
<del>
<ins>
<sub>
<sup>
```

> **Learning step by step — Building my foundation in HTML 🚀**
