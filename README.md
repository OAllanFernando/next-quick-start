
## Next.js App Router Course - Starter

Learning project with Next.js - 16 chapters.

See the release on https://next-quick-start-drab.vercel.app

I was surprised by the capacity of this stack, I really recommend this course to everyone. This will definitely be the next market adoption 



## Reference

 - [learn next.js](https://nextjs.org/learn)
 - [see vercel](https://vercel.com)



## To learn

front stack

- https://nextjs.org/docs/app/building-your-application/optimizing/images
- https://nextjs.org/docs/app/building-your-application/optimizing/fonts
- https://developer.mozilla.org/en-US/docs/Learn/Performance/Multimedia
- https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Web_fonts


navigation
- https://nextjs.org/docs/app/building-your-application/routing/linking-and-navigating#how-routing-and-navigation-works

Error handling - additional content
- https://nextjs.org/docs/app/building-your-application/routing/error-handling
- https://nextjs.org/docs/app/api-reference/file-conventions/error
- https://nextjs.org/docs/app/api-reference/functions/not-found
- https://nextjs.org/docs/app/api-reference/file-conventions/not-found

accessibility
- https://web.dev/learn/accessibility/

authentication by oauth
- https://authjs.dev/getting-started/authentication/oauth

# What is debounce ?

- debounce is a way to prevent that, for example, in search inputs the requisitions to the server will wait until the user ends typing. Not in every keystroke

- pnpm i use-debounce

On admin powershell to run pnpm scrips 

- Set-ExecutionPolicy RemoteSigned -Scope CurrentUser

to block scripts on your machine
- Set-ExecutionPolicy Restricted -Scope CurrentUser


![image](https://github.com/OAllanFernando/next-quick-start/assets/86169747/6462317c-22cf-46da-8dcb-dc5bca911d82)

## Covered topics in every chapter

# 1 - Exploring the project

# 2 - CSS styling
- How to add a global CSS file to your application.

- Two different ways of styling: Tailwind and CSS modules.

- How to conditionally add class names with the clsx utility package.

# 3 - Optimizing Fonts and Images
- How to add custom fonts with next/font.

- How to add images with next/image.

- How fonts and images are optimized in Next.js.

# 4 - Creating Layouts and Pages 
- Create the dashboard routes using file-system routing.

- Understand the role of folders and files when creating new route segments.

- Create a nested layout that can be shared between multiple dashboard pages.

- Understand what colocation, partial rendering, and the root layout are.

# 5 - Navigating Between Pages
- How to use the next/link component.

- How to show an active link with the usePathname() hook.

- How navigation works in Next.js.

# 6 - Setting Up Your Database
- Push your project to GitHub.

- Set up a Vercel account and link your GitHub repo for instant previews and deployments.

- Create and link your project to a Postgres database.

- Seed the database with initial data.

# 7 -  Fetching Data
- Learn about some approaches to fetching data: APIs, ORMs, SQL, etc.

- How Server Components can help you access back-end resources more securely.

- What network waterfalls are.

- How to implement parallel data fetching using a JavaScript Pattern.

# 8 - Static and Dynamic Rendering
- What static rendering is and how it can improve your application's performance.

- What dynamic rendering is and when to use it.

- Different approaches to make your dashboard dynamic.

- Simulate a slow data fetch to see what happens.

# 9 - Streaming
- What streaming is and when you might use it.

- How to implement streaming with loading.tsx and Suspense.

- What loading skeletons are.

- What route groups are, and when you might use them.

- Where to place Suspense boundaries in your application.

# 10 - Partial Prerendering (Optional)
- What Partial Prerendering is.

- How Partial Prerendering works.

# 11 - Adding Search and Pagination
- Learn how to use the Next.js APIs: searchParams, usePathname, and useRouter.

- Implement search and pagination using URL search params.

# 12 - Mutating Data 
- What React Server Actions are and how to use them to mutate data.

- How to work with forms and Server Components.

- Best practices for working with the native formData object, including type validation.

- How to revalidate the client cache using the revalidatePath API.

- How to create dynamic route segments with specific IDs.

# 13 - Handling Errors
- How to use the special error.tsx file to catch errors in your route segments, and show a fallback UI to the user.

- How to use the notFound function and not-found file to handle 404 errors (for resources that don’t exist).

# 14 - Improving accessibility
- How to use eslint-plugin-jsx-a11y with Next.js to implement accessibility best practices.

- How to implement server-side form validation.

- How to use the React useFormState hook to handle form errors, and display them to the user.

# 15 - Adding Authentication
- What is authentication.

- How to add authentication to your app using NextAuth.js.

- How to use Middleware to redirect users and protect your routes.

- How to use React's useFormStatus and useFormState to handle pending states and form errors.

# 16 - Adding metadata

- What metadata is.

- Types of metadata.

- How to add an Open Graph image using metadata.

- How to add a favicon using metadata