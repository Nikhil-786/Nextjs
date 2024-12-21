## Next.js App Router Course - Starter

This is the starter template for the Next.js App Router Course. It contains the starting code for the dashboard application.

For more information, see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

17-12-2024
Adding a primary font
Let's add a custom Google font to your application to see how this works!

In your /app/ui folder, create a new file called fonts.ts. You'll use this file to keep the fonts that will be used throughout your application.

Import the Inter font from the next/font/google module - this will be your primary font. Then, specify what subset you'd like to load. In this case, 'latin':


chapter 4:
Create a dash board round using file-sytem routing.
UnderStand the role of the folder and files while creating new routes segment.
Create a nested layout that can be shared between that can be shared between multiple dashboard pages.
understanding what colocation,patial rendering and root layout are,


notes: 
1 page.tsx is the special files in nextjs that exports react components
2 in next js you can use layout.tsx to UI components and share between multiple pages.
3 the layout component receives child prop.the child can be prop or another layout.
benifits: one benifits of using layout is that only page components updates while layout wont re-render.

20-12-2024
Navigating between pages

How to use the next/link component.
How to show an active link with the usePathname() hook.
How navigation works in Next.js.

Link allows you to do client side navigation.
when the Link code appears in the browers viewports nextjs automatically prefrecteches the code related to the link.
when ever the user click on that link destination page is already loaded in the background which makes page transition in the background near instant.


setting up database
setted postgres database
linked project to database
confifured database and seeded the db.


