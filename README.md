# Code-Refactor
This Code Refactor Project shows how I like to reuse/reorganize code in order to create a more legible code base and accesible website. My job here was to read through the code base and adjust it without making any changes to the page it self. A lot of what I did involved me changing general tags like <div> to Semantic tags like <header>, <section>, and <article> in order to make the code base more legible and the website more accesible. I also went through the CSS style sheet to see what styles could be reused by elements in the HTML. Here is a list of things I went through and changed:
- I started by going through the code and adding comments so I know what is where.
- Next I reoragnized the CSS code in order to keep like items with like items.
- Changed Header <div> to Semantic element <header> while keeping the class name.
- Changed <div> to Semantic element <nav>.
- Changed Hero <div> to Semantic element <section>.
- Changed Content Area <div> to Semantic element <main>.
- Changed each <div> within the Content Area to a <article> Semantic tag.
- Changed Aside <div> to Semantic element <aside>.
- Changed each <div> within the Aside to a <section> Semantic element.
- Changed Footer <div> to Semantic element <footer>.
- Changed the <h2> in the Footer section to <h4> in order to follow sequential order with the other headre elemtns.
- Updated the content in the <title> element to reflect the company and what they do.
- Removed id's within each <article> in the Content Area.
- Added alt attributes to <img> elements in the Content Area.
- After viewing the pictures on the website, I determined that they are all decorational. Therefore their alt attribute's should stay empty.
- Consolidated CSS for the Content Area by making new classes for the HTML, and refering to them in CSS.
- For the Aside section, I changed the parent <div> to Semantic Element <aside>.
- I changed the child <div> elements in the Aside section to <section> Semantic elements.
- Added alt attributes to <img> elements in the Aside Area.
- After viewing the pictures on the website, I determined that they are all decorational. Therefore their alt attribute's should stay empty.
- Consolidated CSS for the Aside Area by making new classes for the HTML, and refering to them in CSS.
- For the Footer section, I changed the parent <div> element to Semantic element <footer>.
- I changed the <h2> tag in the Footer section to a <h4> in order to follow the header hierarchy.

Here is a link to the deployed website: https://calebfunderburk.github.io/Horiseon-Code-Refactor-Fun-Time/

Screenshot of website: 
![Screenshot of Horiseon's Website](horiseon-screenshot.png)