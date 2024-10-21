# #100DaysOfCode Log - Round 1 - Prerna Lele

The log of my #100DaysOfCode challenge. Started on Sept 12 2024

## Log

### R1D0 [Sep 12th 2024]
Started looking into countries api app https://prernalele.github.io/countries-api-main/ 
Problems : Need to look into the theme switcher.

### R1D1 [Sep 13th 2024]
 I had recently used this tutorial to learn how to use context API : https://www.youtube.com/watch?v=aAcI_FdfkA8. 
 So I started with using the same context in passing the "theme" data. Today I only did the ground work
But tomorrow I will make the switcher working
Today's commit : https://github.com/prernalele/countries-api-main/commit/b3775395a7d03a4120e53d7473e2b261c692631a

### R1D2 [Sep 14th 2024]
Today I was able to make the mode/theme switcher functional.  Also made changes to ReadMe
Commit : https://github.com/prernalele/countries-api-main/commit/34f5ce5e855e97a70c67ef1ed37524b34198b608
Thoughts/TODOs : 
The light theme is all over the place currently and would need some fixing.

### R1D3 [Sep 15th 2024]
Finding a bit challenging to make the light mode theme work the way it should. I am passing the theme not as props but using useContext. But the way I am doing isn't DRY so far. 
commit: https://github.com/prernalele/countries-api-main/commit/b65817c34346bd7932300d29d0ccdca2d720cf5b  
Thoughts/TODOs : 
1. The light theme is all over the place currently and would need some fixing.
2. May be I can revisit the tutorial and see what I might be missing. 
3. Observed some other bugs with search bar. 
4. Need to fix the Filter as well
5. The theme should also be saved so it doesn't go away if the user refreshes the page.

### R1D4 [Sep 16 2024]
Day 4 of #100DaysOfCode 

Tried Ironing out the light theme some more. Commit : https://github.com/prernalele/countries-api-main/commit/907b0c8aa6df37da4079b0cda6b9832e6adcc10c

 Definitly a work in progress. Also realizing that the site deployed on github pages isn't picking up the changes when I push changes to github. So right now these changes aren't here https://prernalele.github.io/countries-api-main/ 

Thoughts : 

1. the Cards don't look like the design yet. 
2. I didn't actually spend 2 hours doing this, but I am calling it a win for today.

### R1D5 [Sep 17 2024]

Some more styling changes today. I am baffled about the background-color mystery for when i change themes. I need to look into it some more. But by now i have spent way too much time on it. So from tomorrow I will move on to the Filter changes. 
Commit : https://github.com/prernalele/countries-api-main/commit/f7cec019f282b66bccd62a3a73779be55d066121

Thoughts : 
1. "Why am I struggling with something so simple" was playing in my head
2. I am deciding to move on to Filter feature from tomorrow and revisit this portion some other day (with less coffee in my system may be)

### R1D6 [Sept 19 2024]
Made Filter functional today : 
https://github.com/prernalele/countries-api-main/commit/63dc76eb779f27ac59ca9ac83ae47b6686f14eeb 

ToDos: 
On click for each country , it should open details for that country. 

### R1D7 [Sept 20th 2024]
Added a component and connected it to the clicking of the country card. However I am not sure how I can get the value of the country that's being clicked. 
[commit](https://github.com/prernalele/countries-api-main/commit/382bf781df14d718dc6dda3faabe912727100f3d)

Todos:
1. Find a way to capture the value of the country being clicked
2. Build out the component

### R1D8 [Sept 21th 2024]
Built out the component for single country details page. It has a back button to take to the home page and theme switcher. 

[commit](https://github.com/prernalele/countries-api-main/commit/718796d790ee18b251abe9e4b3d209320142fe35)

ToDos:
1. When I search for the country, and click on it to see the details, it's showing me a different country :D. That's a BUG !! Problem with matching using an index may be ? Need to think this through
2. There is a small detail right now missing on the details page. The neighbouring countries list. The data that's available to me has country code, I have to do a find and bring up the names of those countries and also make them clickable. if the users click on it, what happens to the boolean that keeps track of whether the singlecountry option is being clicked or not (unsure yet).
3. gh-pages isn't actually deploying my changes to the site, need to look into that

### R1D9 [Sep 22 2024]
Styling changes for the country details page. I don't think I was able to succesfully achieve what I had in mind. Will try again tomorrow with a fresh mind. 
[commit](https://github.com/prernalele/countries-api-main/commit/d316189fa7099d89d347c3c7202f908ab4135d1b)

ToDos: 
1. Need to set up the back button
2. What's with the dark theme background
3. Done resolving the deployment delay mystery. hint it was me.

### R1D10 [Sep 23rd 2024]
More Styling changes to make the details page a bit neater. The problem with the theme's backgrounds are fixed. 
[Commit](https://github.com/prernalele/countries-api-main/commit/a392edc1a373bf808767864ed8a06c79d015400d)
ToDo:
1. Need to solve the bug with search and clicking on the search results
2. Clickable buttons to list neighbouring countries

### R1D11 [Sep 24th 2024]
Managed to make everything more horrible , so I had to take my changes back. I will take a fresh look again tomorrow. 

### R1D12 [Sep 25 2024]
Today I restored the way themes were working and made them slightly better. Also I found a probably solution to the bug where , when I search a country and click on it, it was showing me a different details page. However I am yet to properly learn how to update data context. I thought I am doing it right, but it hasn't worked yet. So I need to take a closer look at it tomorrow. 
[Commit](https://lnkd.in/g-RTiHwG)
The above change I haven't yet deployed here https://lnkd.in/eR2dqdNJ

### R1D13 [Sep 26 2024]
Today I was able to fix the bug. Now when you search for a country and click on it, the correct country page opens up
[Commit](https://github.com/prernalele/countries-api-main/commit/6594c4f811da3787efbcf28a259e78b7a5a1a63e)
[Live Link] (https://prernalele.github.io/countries-api-main/)
ToDos : 
1. No color for the open drop down
2. Can we paginate the results we get from API ?
3. The glittching of search bar isn't cool
4. Mobile friendly? .. not yet.
5. In the light mode there the theme isn't getting applied properly

Thoughts :
1. Will I ever finish this Project ?

### R1D14 [Sep 27 2024]
Fixed styling changes for when the search results are displayed

Learning : 
Learned about viewport height and width to solve the issue. However Found another issue with few countries

### R1D15 [Sep 28 2024]
Fixed the background issue when I scroll down
Fixed a bug with the countries who do not have currencies listed
Fixed the one more styling issue with the margins of the home screen
[commit](https://github.com/prernalele/countries-api-main/commit/9c51922829c73e6098a2fe5385fc034b357021be)
ToDo : 
1. List the neighbours and make them clickable

### R1D16 [Sep 29 2024]
Today I worked on introducing debounce like effect using setTimout for the country input box.
Also towards evening I got some more time so I was able to put together logic to map through the bordering countries and find their codes and display them. They aren't clickable yet. That's what's next ! 
[commit](https://github.com/prernalele/countries-api-main/commit/df7ec40f4010df20b5cbd5fafc649ade905d3863)
##### ToDo
When the bordering country is clicked, that should take you to the details page for that country. 

### R1D17 [Sep 30 2024]
1. Fixed a couple of styling issues
2. Fixed the corner case when there are no bordering countries listed
3. Added arround icon for the back button and for some reason this is the one that took most of my time today.
[commit](https://github.com/prernalele/countries-api-main/commit/8d5191572641aa9088f566f2a589fffa96098c0e)
ToDos:
1. Make bordering countries clickable
2. Mobile Friendly.

### R1D18 [Oct 1st 2024]
1. Added media queries to make it more eye pleasing for other screen sizes. [commit: Media Queries](https://github.com/prernalele/countries-api-main/commit/1da5e176a57c4d3eeb5f6746d95b448c7a91c53a)
2. Made border countries clickable. [commit: Make borders clickable](https://github.com/prernalele/countries-api-main/commit/1da5e176a57c4d3eeb5f6746d95b448c7a91c53a)

ToDo: 
1. Search icon appearing outside input box, needs fixing
2. Look for opportunities to refactor.

### R1D19 [Oct 2nd 2024]
Added more media queries and made the search icon appear inside the input box. That was some good learning about CSS positioning. Also made it so that the user preference of theme doesn't go away when they refresh the page
[commit]: (https://github.com/prernalele/countries-api-main/commit/1cda1e7301cf2f609fdef94fe99c56e7a92e6be6)

### R1D20 [Oct 3rd 2024]
This morning I thought I might not get much done today as my daughter is home. But we went to the library towards afternoon, she read a book and I finished the last bit things left in this project. (So thankful for libraries !!!)

I picked up a small portion, making the search partial, and few more styling changes etc and I felt like this might be a good stoping point. I do have some things to fix still . But I submitted it anyway or else this would never get done and I would keep hoping to make it perfect. 

You can see my solution here: https://www.frontendmentor.io/solutions/responsive-mobile-friendly-country-search-with-usecontext-theme-switch-a_nKExfVPF

Any suggestions on how I can improve are welcome! 

###Day 21 of hashtag#100DaysOfCode [Oct 5th 2024]

Took some time to decide next project. I have decided on this one, https://lnkd.in/eeWJ2ina. Today I only got set up. I will start building out from tomorrow. I had a good break and watched a couple of videos on what I can learn next etc.

### Day 22 of #100DaysOfCode [Oct 6th 2024]
I felt like this is a great time to resume "Namaste react" tutorial because I was setting up the new project. It was great, I got to learn about npm , bundlers like Parcel, vite, webpack etc, node_modules, dev dependencies and how the bundlers themselves have dependencies of their own. I am really liking this deep dive approach that Akshay Saini. I am only on the second video and it's very long but much needed. I have come to realize is that practicing coding or any good habit building is kind of like cooking. When we put something on simmering heat, it takes time yet you know the result is going to be good. 

### Day 23 of #100DaysOfCode [Oct 7th 2024]
1. Finished Video 2 part 2 of Namaste React and tried some things related to setup
2. Explored Tailwind for the new product card list project. And went through few tutorials on how to use it

### Day 24 of #100DaysOfCode [Oct 8th 2024]
Today I realized that I had problem with Tailwind setup. The problem was with the way I mentioned paths of the files in it's configuration. It wasn't exactly to obvious for me, so I searched online for why my Tailwindcss classes weren't being recognized and found a solution.  So after correcting that. And reading up on how to set up basic fonts etc, I was able to set up a background and just barely got started with building it out. I still feel pretty happy with today's progress even though there is very little to show. 
[commit](https://github.com/prernalele/product-list-with-cart-main/commit/b1c28a41862b2ff6c870bab0d17ae221dfda1d5e)

### Day 25 of #100DaysOfCode [Oct 9th 2024]
1) Able to fetch the data
2) Able to display details but for some reason my images aren't getting displayed. So tomorrow I need to figure that out. I added them to public folder but still that isn't helping either.
   [commit](https://github.com/prernalele/product-list-with-cart-main/commit/e946b6792f373d67f34b6478644f29e55023b4bd)
   
### Day 26 of #100DaysOfCode [Oct 10th 2024]
Tried fixing the picture not rendering thing to no avail. I kept thinking it HAS to be the path that's wrong and If I could just give a path that it can access then I am golden. 

### Day 27 of #100DaysOfCode [Oct 11th 2024]
**Problem**
I was stuck in the same problem (as yesterday) where the pictures in the image tag were not being rendered. For reference I am working on a project based on React, TailwindCss and Parcel. I saw my code, compared it with previous one. Kept thinking it's just Image tag with an src, so how is it that it works for one project and doesn't work for another. 
**Solution**
Then I thought ok so what do I know so far. I know that my current project is built using Parcel. This is the first time I am using it. Is there something specific about this bundler that I don't know. ( I mean there is a LOT that I don't know but specific to image rendering or build itself). I googled and voila! so many others suffered the same issue. Some conversations suggested to use a parcel plugin "parcel reporter static files copy". So after struggling a bit more about setup etc I followed this documentation : https://www.npmjs.com/package/parcel-reporter-static-files-copy and now my images are rendering. 
**Take aways** : 
1. Static images exist in an asset folder or somewhere. Parcel by itself somehow doesn't have the capability to see it at the time of building. So we need the pluggin, to have it automatically copied to dist folder.
2. Whenever I am getting stuck it's all teaching me something new. Once I solve it I feel almost thankful that the issue even happened, because I would never have learned about it otherwise.
3. 

### Day 28 of #100DaysOfCode [Oct 15 2024]
Struggling with figuring out TailwindCSS classes to have the menu displayed properly. The font isn't right either. 
[commit] | (https://github.com/prernalele/product-list-with-cart-main/commit/f0cb309f485b2e3190033f0d1d7167821ac1a401)

### Day29 of #100DaysOfCode [Oct 16th 2024]
Figured out TailwindCSS quite a bit now. Also took this opportunity to understand flexbox little more. 
[Commit](https://github.com/prernalele/product-list-with-cart-main/commit/54625fd6b51f192ebe2690df0cd044abcf11390e)
My site isn't being published properly. Most likely i am missing some build folder that needs to be on github. I thought it's dist, so I took it out from gitignore. But that didn't fix it. 

### Day 30th of #100DaysOfCode [Oct 17th 2024]
I was able to get it looking closer to the design today. The knowledge of flexbox came in handy. Learned how to extend the TailwindCSS configuration to have a custom color. I am starting to like TailwindCSS. 
[commit](https://github.com/prernalele/product-list-with-cart-main/commit/25f70efc856b9ce601099434dc7166a971114fd4): 
I have devided the rest of the work in the following ToDo list. 
ToDo : 
1. Work on Adding the items to the cart. Display an add button and functionality
2. Display the number of items added on top of the cart
3. Show what's added in the cart and also show quantity below the item that's added.

### Day 31st of #100DaysOfCode [Oct 18th 2024]
Today I made Add to cart functional. 
[commit](https://github.com/prernalele/product-list-with-cart-main/commit/eff1c965a626a09f70e3fbecced92c11a4d62059)

### Day 32nd of #100DaysOfCode [Oct 19th 2024]
Add to cart now has an increment and decrement signs. You can hover over it , add and subtract items. The total number of items are displayed in the cart. 
TODOs:
1. Which item and quantity needs to be displayed in the cart.
2. Individual quantity needs to be displayed in Add to cart button. 

### Day 33rd of #100DaysOf Code [Oct 20th 2024]
The item details component is created. This is still work in progress. Trying to see the most DRY way of displaying items and maintaining and using state wisely. 
TODO: 
1. Right now a total quantity is displayed, not for each item. that needs to be done
2. Need to figure out cart's JSX when it displays items
