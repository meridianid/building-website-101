# Building Website 101

> Crafted with ❤️ by [Meridian.id](http://meridian.id)

##### Table of Contents

1. [Overview](#overview)
2. [Static Website](#static-website)
    * [Gatsby.js](#gatsby.js)
3. [Dynamic Website](#dynamic-website)
    * [Client-Side-Rendering (CSR)](#client-side-rendering-(csr))
    * [Server-Side-Rendering (SSR)](#server-side-rendering-(ssr))
4. [Content Management System (CMS)](#content-management-system-(cms))
    * [Prismic](#prismic)
    * [Contentful](#contentful)
    * [Strapi](#strapi)
    * [Wordpress](#wordpress)
    * [Ghost](#ghost)
    * [Netlify](#netlify)
5. [Deep Comparison](#deep-comparison)
6. [Deployment](#deployment)

## Overview

At Meridian.id, we are using React.js as our official stack for frontend, but a more diverse stack for the backend.

## Static Website

The good old ways of building website. Static website is a website which files are static (pre-built) and served without change from the server.

The term "static" does not mean that your site has no dynamic capabilities. It simply means that that your site consists of a set of "pre-built" files (namely html, js, and css files) that are directly served on request.

### Gatsby.js

[Gatsby.js](https://www.gatsbyjs.org/) is a static site generator based on React.js. It provides a lot useful and easy-to-use plugins that will help us on building high performance and beautiful website. Most of the heavy-lifting works already done, mostly you just need to focus on building your layouts.

#### Pros

* Build website with React.js (means we can take advantages of using the our component library, and the react ecosystem is just awesome)
* It's super fast. Since content is pre-generated, no more time needed to dynamically generate content! This means no database queries, no html templating, etc.
* A lot of plugins to help you improve your website performance (i.e. lazy load images, served various image sizes, etc.)
* SEO friendly
* Lots of deployment options (i.e. [GithubPages](https://www.gatsbyjs.org/docs/how-gatsby-works-with-github-pages/), [Now.sh](https://www.gatsbyjs.org/docs/deploying-to-now/), [Surge.sh](https://www.gatsbyjs.org/tutorial/part-one/#deploying-a-gatsby-site), [Netlify](https://www.gatsbyjs.org/docs/hosting-on-netlify/), and many more). Especially in the early stage of development when you need to show it to the client, you can deploy your website with just single command on the terminal.
* Lots of data sources options, because gatsby just the front-side of the webiste. So, basically you can use anything for the data sources.

#### Cons

* Need a lot of work for online shop or e-commerce functionality. We are working on it. But for now, you are better off with wordpress if you want to have an online shop or ecommerce website.
* Static website (means you need to rebuild and redeploy when you want to update) -- can be solved with CI/CD

#### When to use gatsby

Any kind of static website that doesn't required a really fast changing content, i.e. **Company profile, Event website, and Blog**.
The most important thing to do if you want to build a gatsby website for the client is you need to communicate that to update the content, gatsby website need to rebuild and redeploy. While it's necessarily complex and too long to do that, and it can be overcome with some CI/CD setup, the client still need to aware of that.

## Dynamic Website

Dynamic website is a website which files are dynamically generated with each incoming request on the server and then served.

### Client-Side-Rendering (CSR)

### Server-Side-Rendering (SSR)

## Content Management System (CMS)

### Prismic

[Prismic.io](https://prismic.io) come with a very generous free-tier and webhook integrations with minimal setup. The free-tier also hosted on prismic server with SSL enabled. It's super good for a blogging platform or just a simple company profile that want to have some updated content capabilities.

### Contentful

### Strapi

### Wordpress

Wordpress 5.0 built with RESTful API out of the box that can be consumed by any kind of website and mobile app. When it comes to building an online shop, wordpress really shines because it's plugins.

### Ghost

[Ghost](https://ghost.org/) The hosted solution is rather expensive but you can use it as a self-hosted app for free because it is open source.

### Netlify
[Netlify](https://www.netlify.com)

---

## Deep Comparison

For now, you can view the deep comparison in this [spreadsheet](https://docs.google.com/spreadsheets/d/172LvheWOWiEdzvvoD_XZ6qPCRKRb9IgXvtUjld3xqlY/edit?usp=sharing)

## Deployment

Sometimes you just need to deploy the website that you are building so the client can access it and give some feedback. For this purpose, we have few alternatives other than deploying to the shared hosting or production server.
