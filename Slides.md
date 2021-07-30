# HTC Website Rebuild

Jacob Stordahl

July, 30, 2021

---

## !blue goals

---

### goals

The overall goals of this project are as follows...

- create the optimal user experience for all stake holders
- allow the Web Manager to iterate new web features quickly
- allow the website to remain nimble as marketing strategies shift
-   provide content owners more agency over there pages

---

## !blue how do we accomplish this?

---

## !blue the JAMstack

---

### what is the JAMstack?

Jamstack is an architecture designed to make the web faster, more secure, and easier to scale. It builds on many of the tools and workflows which developers love, and which bring maximum productivity.

---

### what is the JAMstack?

The core principles of pre-rendering, and decoupling, enable sites and applications to be delivered with greater confidence and resilience than ever before.

---

### what is a monolithic web server?

![monolith](https://www.blkcatstudio.com/legacy-server.png)

---

### what is the JAMstack?

![monolith](https://www.blkcatstudio.com/jamstack.png)

---

### what is the JAMstack?

> in short, the JAMstack approach decouples the parts of a website to make those parts easier to manage and iterate on

---

## !blue motivations

---

### motivations

> Performance

- **Problem:** Cascade is built with a monolithic web architecture which for our use case is not needed & is causing performance issues.
- **Solution:** Most if not all pages on hennepintech.edu could be static web pages which could be shipped from a CDN using the JAMstack. This will eliminate a majority of our current performance issues & potentially some cost.

---

### motivations

> Accessibility (a11y)

- **Problem:** currently monitoring accessibiility is done almost by hand with minimal help from paid services like Monsido. This system causes wasted time and allows WCAG compliance issues to be missed
- **Solution:** with a git based deploy process we can integrate many kinds of tests (including a11y tests) to run during every deploy, ensuring that the live site always meets WCAG guidelines and saving the web manager from manually checking code.

---

### motivations

> Content Authoring

- **Problem:** Cascade isn't very intuitive for non-technical content editors. This often leads to confusion, frustration, and eventually getting another person involved to find a resolution, thus using more resources.
- **Solution:** Prismic, the new CMS, is very intuitive from a content editing standpoint and will remove a lot of the complexity that Cascade currently has. I would also propose we create short tutorial videos for the new CMS so content owners can hopefully unblock themselves from issues.

---

### motivations

> Developer Experience

- **Problem:** the current code base has been poorly maintained and has no system for code authoring at all. this likely stems from a lack of documentation of process, or a lack of process in general
- **Solution:** the proposed rebuild will be documented from front to back which will allow new development focused stake holders to make decisions that fit the system we will design

---

### motivations

> Design System

- **Problem:** the User Interface of the current website is not dictated by any system and is rather random. Button styles are not consistent, text styling is not structured, to name a few issues.
- **Solution:** along with the rebuild, I would propose developing a formal, documented design system for HTC web products, ideally in collaboration with the team building the student mobile app with input from the marketing team

---

## !blue next steps

---

### next steps

- Web Manager will create a full write up descibing the design of the entire system including deployment, DNS managment, and Content Owner workflow
- Web Manager in collaboration with Creative Director &amp; VP of Technology (and any other applicable parties) to create a timeline for the rebuild and transition off of Cascade

---

## !blue thank you!
