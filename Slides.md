# HTC Website Rebuild

Jacob Stordahl

July, 30, 2021

---

## !blue goals

---

### goals

The overall goals of this project are as follows...

-   create the optimal user experience for all stake holders
-   provide flexibility for marketing content to be used across multiple channels
-   allow the website to remain nimble as marketing strategies shift
-   provide content owners more agency over there pages

:: Speaker note aka Comment

---

## !blue motivations

---

### motivations

> Performance

-   __Problem:__ Cascade is built with a monolithic web architecture which for our use case is certainly not needed
-   __Solution:__ Most if not all pages on hennepintech.edu could be static web pages which could be shipped from a CDN without a web server

---

### motivations

> Accessibility (a11y)

-   __Problem:__ currently monitoring accessibiility is done almost by hand with minimal help from paid services like Monsido
-   __Solution:__ with a git based deploy process we can integrate many kinds of tests (including a11y tests) to run during every deploy, ensuring that the live site always meets WCAG guidelines

---

### motivations

> Content Authoring

-   __Problem:__ Cascade isn't designed with non-technical content editors in mind. This often leads to confusion, frustration, and eventually getting another person involved to find a resolution, thus creating wasted time.
-   __Solution:__ with a headless CMS, we can customize the CMS in anyway so it makes semse for our specific use case &amp; our content editors

---

### motivations

> Developer Experience

-   __Problem:__ the current code base has been poorly maintained and has no system to code authoring at all. this likely stems from a lack of documentation of process, or a lack of process in general
-   __Solution:__ the proposed rebuild will be documented from front to back which will allow new development focused stake holders to make decisions that fit the system we'll design

---

### motivations

> Design System

-   __Problem:__ the User Interface of the current website is not dictated by any system and is rather random. Button styles are not consistent, text styling is not structured, to name a few issues.
-   __Solution:__ along with the rebuild, I would propose developing a formal, documented design system for HTC web products, ideally in collaboration with the team building the student mobile app with input from the marketing team

---

## !blue next steps

---

### next steps

-   Web Manager will create a full write up descibing the design of the entire system including deployment, DNS managment, and Content Owner workflow
-   Web Manager in collaboration with Creative Director &amp; VP of Technology (and any other applicable parties) to create a timeline for the rebuild and transition off of Cascade

---

## !blue thank you!