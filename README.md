<div align="center"><h1>Web Dev Starter Guide / Advice:</h1></div>

<h3>Web Development is a really fun subfield to know about, but at the same time, it's an ever-growing subfield, so understanding the pipeline to learn it can be a bit confusing. Since it can get so confusing, I just wanted to share the path that I personally took to learn and understand it better.</h3>

-----

## Table of Contents:

- [First Steps (HTML, CSS, JS)](#first-steps)
- [Switching over to industry-standard Tools (React.js, TypeScript, ESLint)](#industry-standard-tools)
- [Moving to advanced tools with Frameworks and Component Libraries (Next.js, TailwindCSS, Component Libraries)](#advanced-tools-and-frameworks)
- [Wireframing and Designing (Figma)](#wireframing-and-designing)
- [Deploying and Hosting your Site (Vercel, Cloudflare, GitHub Pages)](#deploying-and-hosting-your-site)
- [Backend/Fullstack Development](#backendfullstack-development)
- [Databases](#databases)
- [Build Tools and Automation](#build-tools-and-automation)

-----

## First Steps (Bare HTML, CSS, JS): <a name="first-steps"></a>

My personal first step into web development was a state of confusion for myself about where I should start and what I should build. After going down several rabbit holes that seemed too complex for me, I came across a portfolio site template on replit: [Portfolio Website Template](https://replit.com/@AshishJob/Portfolio-Website-Template) which was built on bare HTML, CSS, and JavaScript, of which I knew none. BUT I just messed around with different HTML tags and CSS definitions and looked into [HTML documentation](https://developer.mozilla.org/en-US/docs/Web/HTML), [CSS documentation](https://developer.mozilla.org/en-US/docs/Web/CSS), and [JavaScript documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript) to understand what changes I could make. In case you aren't familiar with each technology, HTML is HyperText Markup Language which is a tool to mark the content and structure of pages, CSS is Cascading Style Sheets which is a tool to style each page with colors and features, and JavaScript is a programming language that works for the functions under the cover and very generally used in web development.

### TLDR:
- [Replit Template](https://replit.com/@AshishJob/Portfolio-Website-Template) is a useful source to tinker and experiment with.
- [HTML - HyperText Markup Language](https://developer.mozilla.org/en-US/docs/Web/HTML) is the programming language to structure pages.
- [CSS - Cascading Style Sheets](https://developer.mozilla.org/en-US/docs/Web/CSS) is the programming language to style pages.
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) is the programming language to work on the functions under the cover.

<h2><a href="https://ashishjob.web.app/">My first website</a> and its <a href="https://github.com/Ashishjob/Old-Portfolio-Website">repository.</a></h2>

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/50a5d622-8435-401a-a78a-eb374365da18)
[![Tech Stack](https://skillicons.dev/icons?i=js,html,css)](https://skillicons.dev)

-----

## Industry-Standard Tools (React.js, TypeScript, ESLint): <a name="industry-standard-tools"></a>

After a little while, I got bored with my project and wanted to switch to a project that I fully made on my own from scratch. I kept hearing about some industry-standard choices, and at the same time, I got placed into my University's ACM Organization's WebDev Committee that had a tech stack including, but not limited to, React.js, TypeScript, and ESLint, so that definitely helped the learning process. I still definitely had to reach out to some people to help me out on getting over the learning curve, but learning it definitely scales up your skills to make yourself more robust as a web developer. I read up on [React documentation](https://legacy.reactjs.org/tutorial/tutorial.html), some [TypeScript documentation](https://www.typescriptlang.org/docs/), and [ESLint documentation](https://eslint.org/docs/latest/), and to roughly explain each: React.js is a JavaScript library built for making UI that pretty much combines HTML files and JS/TS files into one JSX/TSX file, and it is also component-based meaning that you can reuse components that you create instead of entirely recreating things that you may reuse; TypeScript is like a superset of JavaScript where you static typing is also introduced, making it a more versatile language; Finally, ESLint is a code analyzing tool that's essential functionality is to catch common programming errors, enforce style guidelines, and improve overall code quality.

### TLDR:
- [React.js](https://legacy.reactjs.org/tutorial/tutorial.html) is a JavaScript library to optimize web development.
- [TypeScript](https://www.typescriptlang.org/docs/) is a programming language built off of JavaScript, but improved to become more versatile.
- [ESLint](https://eslint.org/docs/latest/) is a code analyzing tool to help you write cleaner code.

<h2><a href="https://github.com/Ashishjob/CougarCS-AdminPortal">The repository.</a></h2>

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/f2dd5cdc-cb4c-40dc-962f-c36950b79e49)
[![Tech Stack](https://skillicons.dev/icons?i=ts,react)](https://skillicons.dev)
<img src="https://github.com/Ashishjob/webdev-advice/assets/114624617/18180c1e-d945-404a-80b6-7ca6c0a2b219" alt="Tech Stack" style="width: 50px; height: 50px;">

-----

## Advanced Tools and Frameworks: <a name="advanced-tools-and-frameworks"></a>

Turns out I got bored of the industry-standard practices, and found out about Next.js, and it just looked really cool to me. I found out it was like React but with enhancements, pretty much like the JavaScript-TypeScript relationship and it's an actual framework instead of a library this time. For the other 2 parts, it was again another coolness factor that I personally took into account with their logos, but after using them, they just made life so much easier, that I started to have them as my crutch when it came to web development. With knowledge from the prior steps, these weren't hard to learn conceptually, but they just have a broader selection of available features, so really just researching what features are available and what you can experiment with is the best resource to get better accustomed to them. Here are their documentations: [Next.js documentation](https://nextjs.org/docs), [TailwindCSS documentation](https://tailwindcss.com/docs/installation), and for the component libraries, there are so many that it really comes down to personal preference and specific features that you may be looking to add into your website, but some popular ones include [shadcn/ui](https://ui.shadcn.com/docs), [Radix UI]([url](https://www.radix-ui.com/primitives/docs/overview/introduction)), [MUI](https://mui.com/material-ui/getting-started/), [Aceternity UI](https://ui.aceternity.com/), and many more. Finally to give an explanation on what each is: Next.js is a web development framework built on top of React that adds features like server-side rendering, static site generation, API routes, and file-based routing; TailwindCSS is a utility-first CSS framework that uses predefined classes directly in HTML to style components, speeding up development and ensuring consistent styling. Finally, Component libraries provide pre-built, customizable UI components that speed up development by offering ready-made solutions for common UI elements like buttons, forms, and modals.

### TLDR:
- [Next.js](https://nextjs.org/docs) is a web development framework built off of React that further accelerates development.
- [TailwindCSS](https://tailwindcss.com/docs/installation) is a CSS framework that merges CSS with HTML.
- Component Libraries are libraries of already made components, speeding up frontend development with standard and reusable components.

<h2><a href="https://git-study-self.vercel.app/">The website's link</a> and its <a href="https://github.com/Brodypen/GitStudy">repository.</a></h2>

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/f71c5750-7da5-4c6b-91ad-2e2552f24a76)
[![Tech Stack](https://skillicons.dev/icons?i=next,tailwind)](https://skillicons.dev)
<img src="https://github.com/Ashishjob/webdev-advice/assets/114624617/59cc6306-f1a1-4ef7-8870-44ae467e4212" alt="Tech Stack" style="width: 50px; height: 50px; border-radius: 50%; display: block; overflow: hidden;">

-----

## Wireframing and Designing: <a name="wireframing-and-designing"></a>

Developers aren't the only thing that websites need, in reality, if the website doesn't look so good, users won't really be attracted to it at all, and having no users pretty much nearly defeats the purpose of developing it in the first place. So tools like Figma are really helpful when it comes to prototyping your product, optimizing it to look better, ensuring a responsive design, and collaborating if it's a team-based project. With the prototyping, you can take it in different stages from low-fidelity designs, which are extremely minimally detailed blueprints that contain what major components each page needs more or less, to higher-fidelity designs, which are the designs that will pretty much be what the site will look like at the end, so that you can see the lifecycle of the product and give/receive feedback on it to always optimize it before you put it out to production or even development. In addition to just the fidelity to the contents on the page, there's also prototyping/wireframing by which you can map out the whole user flow to see the product from the eyes of the public, and see if your page has a coherent path to everything that you have available to the viewer. When it comes to the collaboration side of it, an iterative design process is brought to the table, where changes aren't realized after they have already been developed, but rather you see changes that need to be made much earlier and you can save a lot of the time needed for the development. Finally, there isn't much developer type of documentation on this type of process, but Figma does have a [Figma Learn page](https://help.figma.com/hc/en-us) with resources.

### TLDR:
- Designing/Wireframing saves a lot of time and effort in the development stages by allowing developers/designers to work together if there are both, prototype their ideas, and continuously improve on these ideas too.

<h2><a href="https://www.figma.com/proto/tbX9jNSBJlXaXvGx6PWDHX/bloom---Catalyst-Designathon?embed_host=share&kind=proto&node-id=65-1407&page-id=2%3A4&scaling=scale-down&starting-point-node-id=65%3A1407&t=3sF0CIwQ0N8xbXHg-1&type=design">A sample prototype that I got to collaborate on.</a></h2>

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/4712c291-d8e4-4ff0-b84c-b05185863acc)
[![Tech Stack](https://skillicons.dev/icons?i=figma)](https://skillicons.dev)

-----

## Deploying and Hosting Your Site: <a name="deploying-and-hosting-your-site"></a>

It's one thing to develop your site, but you don't want to just keep it on localhost, cause sending that link to others will just lead them to a classic "This site can't be reached" page (unless they just so happen to be running their code on that localhost too). This is exactly where the deployment services like Vercel, Cloudflare, and GitHub Pages come into play for most applications, usually, a few more steps are taken with full-stack projects since each part has to be hosted from the frontend side that shows the data to the backend side that fetches or makes changes to the data to the database that holds all the data itself. Moreover, deploying ensures your site is secure, performs well, and can handle traffic spikes effectively. Whether you're showcasing a personal portfolio or launching a business application, choosing the right deployment strategy ensures your site remains accessible and functional to users worldwide. Finally, it doesn't just keep your service available to users, but developers can use it to perform analytics reviews on their users too, where you can see things like what device, browser, or even operating systems the viewers are on when they access your service as well as metrics such as user traffic within certain times or locations, how they may have been routed to the page, and what the standard user flow may look like on your page.

### TLDR:
- Deploying your website is what makes it public to be viewed by everyone that has access to the website, and can offer great insight into metrics that users can populate for your website too.
- Some services include: [Vercel](https://vercel.com/docs/deployments/overview), [Cloudflare](https://developers.cloudflare.com/pages/), and/or [GitHub Pages](https://docs.github.com/en/pages).

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/7bb6954e-d862-4164-b65b-679e5e2139b7)
[![Tech Stack](https://skillicons.dev/icons?i=vercel,cloudflare,github)](https://skillicons.dev)

-----

## Backend/Fullstack Development: <a name="backendfullstack-development"></a>

This is honestly where the more standard developer side comes out. You'll be dealing a lot more with dynamic pages where data becomes paramount — how you store it, fetch it, manipulate it, and more. In full-stack development, the backend serves as the engine room, processing requests, managing databases, and ensuring smooth interactions between the user interface and server-side logic. It acts as the middleman between the database and the frontend, determining what data users can see and interact with. Technologies like [Node.js](https://nodejs.org/), [Django](https://www.djangoproject.com/), or [Flask](https://flask.palletsprojects.com/) are common choices for backend frameworks, each offering robust tools for handling data storage and retrieval. Understanding APIs (Application Programming Interfaces) is also crucial here; they facilitate communication between different parts of your application stack, ensuring seamless data flow. Whether you're building a web app, an e-commerce platform, or a complex enterprise solution, mastering backend and full-stack development empowers you to create scalable, efficient, and responsive applications that meet modern user expectations.

### TLDR:
- Backend development manages data and processes for dynamic web applications, and it connects the database to the frontend through APIs, ensuring seamless user interactions.
- Commonly used backend technologies include: [Node.js](https://nodejs.org/), [Django](https://www.djangoproject.com/), or [Flask](https://flask.palletsprojects.com/)

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/be69fe0c-fdf8-40aa-ade8-8ab99f79c8ed)
[![Tech Stack](https://skillicons.dev/icons?i=nodejs,django,flask,express)](https://skillicons.dev)

-----

## Databases: <a name="databases"></a>

In addition to just the backend, databases are crucially important. There's no point in fetching your data if there is nowhere to fetch it from — you simply can't fetch water from a well if the well doesn't even exist to begin with. Databases play a foundational role in storing and organizing data for retrieval and manipulation. They range from Relational Databases like [MySQL](https://www.mysql.com/) and [PostgreSQL](https://www.postgresql.org/) to Non-relational Databases such as [MongoDB](https://www.mongodb.com/) and [Redis](https://redis.io/), each offering different strengths suited to specific application needs. There's also a wide range of specialized databases like [key-value stores](https://redis.io/), [time-series databases](https://prometheus.io/docs/introduction/overview/), [graph databases](https://neo4j.com/), and more, each optimized for specific data models and query patterns. Understanding query languages like SQL (Structured Query Language) or NoSQL variants is essential for efficiently retrieving and manipulating data within these databases. By mastering database technologies, developers ensure robust data management that supports the functionality and scalability of their applications.

### TLDR:
- Databases store and manage data for applications, supporting various data models and query patterns, and can range from traditional relational databases to specialized systems like key-value stores and graph databases.
- Commonly used Relational Database technologies include [MySQL](https://www.mysql.com/) and [PostgreSQL](https://www.postgresql.org/).
- Commonly used Non-relational Database technologies include: [MongoDB](https://www.mongodb.com/), [Redis](https://redis.io/), [Prometheus](https://prometheus.io/docs/introduction/overview/), and [Neo4j](https://neo4j.com/)

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/4faeacbb-feda-4a2b-873d-9465472ab9bb)
[![Tech Stack](https://skillicons.dev/icons?i=mysql,postgresql,mongodb,redis,prometheus,neo4j)](https://skillicons.dev)

-----

## Build Tools and Automation: <a name="build-tools-and-automation"></a>

In modern web development, efficient build tools and automation are crucial for streamlining workflows and ensuring quality in software projects. Package bundlers like [Vite](https://vitejs.dev/) optimize frontend performance by bundling modules on demand, enhancing development speed. Testing frameworks such as [Jest](https://jestjs.io/) facilitate comprehensive unit and integration testing, ensuring robust code quality and reliability. For behavior-driven development (BDD), frameworks like [Cucumber](https://cucumber.io/) enable collaboration between developers and stakeholders through executable specifications. Continuous Integration and Continuous Deployment (CI/CD) pipelines, managed by tools like [Jenkins](https://www.jenkins.io/), automate the build, test, and deployment processes, enhancing efficiency and reducing errors in software delivery. By integrating these tools into your development stack, you can optimize productivity, maintain code integrity, and deliver high-quality applications that meet user expectations.

### TLDR:
- Build tools and automation streamline development workflows, improving efficiency and software quality.
- Tools like [Vite](https://vitejs.dev/), [Jest](https://jestjs.io/), and [Cucumber](https://cucumber.io/) optimize frontend performance, ensure code reliability through testing, and support behavior-driven development respectively.
- CI/CD pipelines with tools like [Jenkins](https://www.jenkins.io/) automate build, test, and deployment processes, enhancing development speed and reducing errors.

![image](https://github.com/Ashishjob/webdev-advice/assets/114624617/83d0ff80-be14-4f85-b94a-73291f95ff18)
[![Tech Stack](https://skillicons.dev/icons?i=vite,jest,jenkins)](https://skillicons.dev)

-----
