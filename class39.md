### Create a Next.js App:
- To build a complete web application with React from scratch, there are many important details you need to consider:
- Code has to be bundled using a bundler like webpack and transformed using a compiler like Babel.
- You need to do production optimizations such as code splitting.
- You might want to statically pre-render some pages for performance and SEO. You might also want to use server-side rendering or client-side rendering.
- You might have to write some server-side code to connect your React app to your data store.
### Next.js: The React Framework:
Enter Next.js, the React Framework. Next.js provides a solution to all of the above problems. But more importantly, it puts you and your team in the pit of success when building React applications.
Next.js aims to have best-in-class developer experience and many built-in features, such as:
- An intuitive page-based routing system (with support for dynamic routes)
- Pre-rendering, both static generation (SSG) and server-side rendering (SSR) are supported on a per-page basis
- Automatic code splitting for faster page loads
- Client-side routing with optimized prefetching
- Built-in CSS and Sass support, and support for any CSS-in-JS library
- Development environment with Fast Refresh support
- API routes to build API endpoints with Serverless Functions
- Fully extendable
- Next.js is used in tens of thousands of production-facing websites and web applications, including many of the world's largest brands.
### Create a Next.js app
To create a Next.js app, open your terminal, cd into the directory you'd like to create the app in, and run the following command:
```
npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn-starter/tree/master/learn-starter"
```
- To run the local Host use this command : `npm run dev`
#### Download Your Profile Picture:
First, let's retrieve your profile picture.
- Download your profile picture in .jpg format (or use this file).
- Create an images directory inside of the public directory.
- Save the picture as profile.jpg in the public/images directory.
- The image size can be around 400px by 400px.
- You may remove the unused SVG logo file directly under the public directory.
### Image Component and Image Optimization
- next/image is an extension of the HTML <img> element, evolved for the modern web.
- Next.js also has support for Image Optimization by default. This allows for resizing, optimizing, and serving images in modern formats like WebP when the browser supports it. This avoids shipping large images to devices with a smaller viewport. It also allows Next.js to automatically adopt future image formats and serve them to browsers that support those formats.
- Automatic Image Optimization works with any image source. Even if the image is hosted by an external data source, like a CMS, it can still be optimized.
### Using the Image Component
#### Instead of optimizing images at build time, Next.js optimizes images on-demand, as users request them. Unlike static site generators and static-only solutions, your build times aren't increased, whether shipping 10 images or 10 million images.
- Images are lazy loaded by default. That means your page speed isn't penalized for images outside the viewport. Images load as they are scrolled into viewport.
- Images are always rendered in such a way as to avoid Cumulative Layout Shift, a Core Web Vital that Google is going to use in search ranking.
#### This page is using a library called styled-jsx. It's a "CSS-in-JS" library — it lets you write CSS within a React component, and the CSS styles will be scoped (other components won't be affected).
 Next.js has built-in support for styled-jsx, but you can also use other popular CSS-in-JS libraries such as styled-components or emotion.
### Writing and Importing CSS
- Next.js has built-in support for CSS and Sass which allows you to import .css and .scss files.
- Using popular CSS libraries like Tailwind CSS is also supported.
- In this lesson, we'll talk about how to write and import CSS files in Next.js. We'll also talk about Next.js's built-in support for CSS Modules and Sass. Let's dive in!
