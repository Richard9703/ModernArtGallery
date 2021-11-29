# RPVillanuevueva_Project1

# Modern
Modern is a free online art gallery that showcases a variety of artists. It is a website that offers a wide array of information about the featured artists and how their works have been translated in recent times.  

## Motivation
My main inpsiration for this website was due to the lack of online galleries that are online. It is difficult to appreciate certain artwork without travelling to the country it is located in and that is difficult for some. The website is made for people who would prefer to have a visual and informative experience in the comfort of their homes. 

# Build 
The main idea for the page is to be a single scroller. The top section of the page will be a nav bar on a background image It will have the web page title in the middle of the page. You will be able to use the navbar to navigate the page as it will be a single scroller. It will include links to wiki pages for the artists and you can view a collection of their works in the online gallery. At the end of the page you will find the information page just talking about what the website is and why it was made. The contact form at the end is there if you would like to make suggestions or have any inquries or issues in regards to the website.

The navbar I chose was a simple sticky nav bar. It is also responsive in 3 screensizes: Laptop/Computer, iPad and Smartphones. I chose this as it was a single scroller and I wanted it to be easy for users to navigate the website without ever needing to scroll up or down the website. 
![image](https://user-images.githubusercontent.com/91730394/143792661-6d472484-1a72-45aa-9378-69fc23504cd2.png)


![image](https://user-images.githubusercontent.com/91730394/143299002-0d153571-e511-4f0a-865d-bc3bfc4cc4c0.png)

Then the Artists section will feature the 3 artists and introduce them briefly. It's not final if it will be a round border or a rectangular

![image](https://user-images.githubusercontent.com/91730394/143299303-cb540a0b-6c61-49e3-9ab8-e4cb63ea07dc.png)

The Gallery section will showcase 3 artworks from the 3 artists in a grid/column view.

![image](https://user-images.githubusercontent.com/91730394/143299447-0e98d1fa-baa9-4026-acc1-4765d35ac5b6.png)

# Update
Added texts and background images to landing page. I used 3 colors as a base. I have also a clickable place holder link that will scroll down to the gallery page. There is an animation added to the first 3 texts which reveals it when you first load the page.

## Colors used
-![#F0F5F7](https://via.placeholder.com/15/F0F5F7/000000?text=+) `#F0F5F7`
-![#9F9BC0](https://via.placeholder.com/15/9F9BC0/000000?text=+) `#9F9BC0`
-![#0000](https://via.placeholder.com/15/00000/000000?text=+) `#00000`

![image](https://user-images.githubusercontent.com/91730394/143300188-00b5e021-36f4-487b-baed-2019769c21fb.png)

The base page for the artists section. The goal is to showcase the 3 artists and provide small information on them within a container. I applied a gradient overlay and z-index as some images were too bright and too dark to use white texts.
![image](https://user-images.githubusercontent.com/91730394/143301608-a6ea5979-c079-4892-89d2-410bb4caec69.png)

I ended up making cards for the 3 artists and added a background image behind each. I used an artist icon to fill the top area above the headers. I added an overlay and lowered it's opacity to make it lighter for the first card as it was too bright and a little bit darker for the other 2 cards. 
![image](https://user-images.githubusercontent.com/91730394/143316510-25e9d479-d3b9-49fe-9386-06443e7d6f56.png)

The gallery section is to showcase artworks from the artists. It will be a grid/column style where you will be able to zoom // Had issues with the gallery and container as they were overlapping a lot. I fixed this by making sure i styled it's own class separate from the main .container in the css. 


![image](https://user-images.githubusercontent.com/91730394/143316687-bddbada5-973e-4e1b-b21a-b96aad4dfe6d.png)
The final product for the gallery page was a carousel with buttons that show which is the active page at the bottom. This was done with bootstrap and some custom classes as I had to merge it with the existing container in the page. 
![image](https://user-images.githubusercontent.com/91730394/143792357-3295fb80-d8ed-458a-99c2-0f700b1a4a1a.png)




