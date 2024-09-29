# Assignment 6 Challenges

A stumbling block I encountered while completing this assignment was aligning the navigation. I couldn't get the h1 tag to sit next to the navigation links due to the flexbox. However, I realized that my h1 tag was not nested within the nav tag which was causing them not to align. After I fixed this, everything aligned correctly. 

Another issue I had was keeping the aside element next to the main instead of under it by using flexbox. While the body is contained in a flexbox I realized that for main and aside element selectors in my CSS file,I had removed the "display:inline-block" property which caused the aside to remain at the bottom of the page instead of next to the main. 