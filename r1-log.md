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

