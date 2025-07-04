📌 Basics & Core Concepts (1-15)
What is Next.js, and why would you choose it over Create React App?

Explain how Next.js handles server-side rendering (SSR) vs static site generation (SSG).

What are the main differences between getServerSideProps and getStaticProps? Give scenarios where you’d use each.

How does Next.js support incremental static regeneration (ISR)? Describe a real use case.

What is file-based routing in Next.js?

How would you create a dynamic route in Next.js for blog post URLs like /posts/[slug]?

Explain how API routes in Next.js work and when you’d use them over a separate backend.

Describe how _app.js and _document.js files differ in Next.js.

What is the purpose of Head from next/head? How would you dynamically set meta tags for SEO?

How do you perform redirects in Next.js using next.config.js?

What happens when you return a 404 in getServerSideProps?

Explain shallow routing with router.push in Next.js. When would you use it?

How would you preload a page or component in Next.js for better UX?

What does the Link component from next/link do? How is it different from HTML <a>?

Can you explain how Next.js optimizes images using the next/image component?

📌 Real-World Scenarios: Data & Performance (16-30)
How would you handle data fetching in a Next.js app that needs both SSR and client-side updates?

Your page depends on user authentication; should you use SSR or SSG? Why?

How do you implement caching strategies in Next.js with getStaticProps or getServerSideProps?

What are the trade-offs of ISR vs SSR for a frequently updated product catalog?

Describe a scenario where you need to revalidate ISR pages manually. How would you do it?

Your marketing team wants different meta tags per page for SEO—how do you implement this in Next.js?

How do you add global styles and CSS frameworks like Tailwind CSS in a Next.js project?

How can you optimize font loading in Next.js for performance?

A page is slow because of a large third-party script. How would you defer or lazy-load it in Next.js?

How does Next.js support AMP pages? Would you recommend using AMP in 2025?

Explain how Next.js uses React Server Components (RSC) starting with Next.js 13.

You notice cumulative layout shift (CLS) issues on your Next.js pages—what causes this and how would you fix it?

Your site has thousands of product pages—how do you generate static pages efficiently with getStaticPaths?

A third-party API is rate-limited, but you need fresh data every page load—how would you approach SSR without overwhelming the API?

How do you implement error handling for API routes to provide friendly messages on the frontend?

📌 Advanced & Architecture (31-45)
Explain middleware in Next.js 12+ and give a practical use case.

How do you restrict access to certain routes based on user roles in Next.js?

Describe the difference between client-side and server-side navigations in Next.js apps.

How does Next.js handle environment variables, and what’s the difference between NEXT_PUBLIC_* and regular variables?

How do you integrate Next.js with a headless CMS like Strapi, Contentful, or Sanity?

Explain the Next.js Image Optimization API flow—what happens when a user requests an image?

You need to support internationalization (i18n) for multiple languages—how do you do it in Next.js?

How do you implement dark mode globally in a Next.js app with persisted state?

What is the difference between client-side state management libraries (e.g., Redux, Zustand) vs server state in Next.js apps?

Describe a scalable folder structure for a large Next.js application.

How would you add TypeScript support to a Next.js project?

You have a legacy React component not compatible with SSR; how do you lazy-load it only on the client?

What are rewrites in next.config.js and how do they differ from redirects?

How do you set up absolute imports and path aliases in Next.js?

Explain how Next.js’s App Router (app/ directory) introduced in Next.js 13 changes routing compared to the pages/ directory.

📌 DevOps, Security & Miscellaneous (46-60)
Describe the deployment process of a Next.js app on Vercel.

How do you deploy a Next.js app on AWS or Azure without using Vercel?

Your Next.js site faces DDoS attacks; what CDN or security measures would you use?

How would you implement authentication in Next.js using NextAuth.js?

Explain a scenario where static HTML export (next export) is suitable and its limitations.

How would you handle GDPR cookie consent banners in a Next.js app?

Explain SSG fallback behavior (fallback: true vs false vs blocking) with getStaticPaths.

How do you secure sensitive API routes in Next.js?

Describe how you would do A/B testing in Next.js without affecting SEO.

How do you analyze and reduce your Next.js bundle size?

How would you handle rate limiting in Next.js API routes?

What is the purpose of next.config.js’s basePath, and when would you use it?

Explain Next.js Edge Functions and when you’d prefer them over serverless functions.

You need a multi-tenant SaaS app where each customer has a subdomain—how do you handle routing in Next.js?

Your team wants to migrate a monolithic React SPA to Next.js; what steps would you recommend?

------------------------------------------------
🔴 Lekin kuch aur bhi zaruri cheezein hain jo interview ke alawa tumhe differentiate karengi aur high-paying job dilayengi:
1️⃣ System design knowledge – jaise scalable architecture for Next.js apps with CDN, caching, load balancing, micro-frontends.
2️⃣ Soft skills & problem solving – communication, explaining architecture, debugging approach.
3️⃣ JavaScript & React deep knowledge – because Next.js is React-based, toh React fundamentals strong hone chahiye.
4️⃣ Backend basics – agar tum API routes likh rahe ho, toh security, rate limiting, authentication concepts important hain.
5️⃣ Testing – Cypress, Jest ya Playwright se Next.js apps ka testing setup kaise karte ho.
6️⃣ CI/CD – GitHub Actions, Vercel integrations ya AWS pipeline knowledge.