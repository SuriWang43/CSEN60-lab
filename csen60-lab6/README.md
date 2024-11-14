```
npm install
npm run dev
```

```
open http://localhost:3000
```
https://docs.google.com/document/d/1cjvDwAp2Kt7_hWP22QXkGqtWD8n3-tNT7McFbYbm46s/edit?usp=sharing

##

“What’s the difference between how your website is rendered in Lab 3 vs. Lab 6?”
- The link is different from the exact directory where this file is located in my laptop to a link starts with localhost:3000. 
- When inspecting the two wesbite, in the network section, lab 3 website barely shows activities while lab 6 shows lots of activities represented by white, gree, blue strings.
- Lab 6 use server-side rendering to generate dynamic content, while Lab 3 rely on client-side JavaScript frameworks.
- For example for Lab 6 website, when a user makes a request by visiting a URL, the server generates the HTML, CSS, and JavaScript on the fly before sending it to the browser. Hono handle request for dynamic data from a database or API.
- For Lab 3 website, it can either be pre-rendered at build time or only serves static files (which resources cannot modify or required processing before being delivered to the user browsers).
