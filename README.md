# Blog

Technology Blog built following JAMstack architecture.

### What is JAMstack?
> Modern web development architecture based on client-side **JavaScript**, reusable **APIs**, and prebuilt **Markup**.
> --<cite>[JAMstack.org](https://jamstack.org/)</cite>

* `JavaScript` : Any dynamic programming during the request/response cycle is handled by JavaScript, running entirely on the client. This could be any frontend framework, library, or even vanilla JavaScript.
* `APIs` : All server-side processes or database actions are abstracted into reusable APIs, accessed over HTTPS with JavaScript. These can be custom-built or leverage third-party services.
* `Markdown` : Templated markup should be prebuilt at deploy time, usually using a site generator for content sites, or a build tool for web apps.

JAMstack essentially is a new way of building websites by removing the tight coupling between frontend & backend using __APIs__ which are dynamically fetched using client-side __JavaScript__ to fill in predefined __Markup__ templates.

---

We'll be building our blog using GatsbyJS with custom-built API as data source.
