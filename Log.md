### DH Exploration Exercise Log

Name: Kaliyah Desormeaux 
Date: June 15th, 2022
Archive (the foundation of the DH Exploration Exercise: [Abby Bright’s Diary](http://www.kansasmemory.org/item/223662)

## Starting Stage of Using Wget

I began working with Wget to retrieve the content of [Abbie Bright’s Diray](http://www.kansasmemory.org/item/223662) from [this](https://www.kansasmemory.org/item/223662) webpage. 
I then started following the _Basic Usage_ directions in the [Wget tutorial](https://craftingdh.netlify.app/tutorials/wget/). 

And that didn’t work:
![](https://user-images.githubusercontent.com/105247273/174705435-2509d5fd-b1a5-40af-bee6-cd67a55dfb01.png)


### Using Wget with a List of URLs


I then knew I had to use Wget through a list of URLs for this to work. From the webpage of [Abbie Bright’s Diary](http://www.kansasmemory.org/item/223662), I clicked on inspect image and found the actual format of the URL; that's where I found the actual image, which gave me the actual number for the image, rather than the URL in the tab (which merely provided me with the website for the Diary). 
I wrote out each diaries specific URL 86 times as I couldn’t figure out python to generate a list of URLs (which I know python is a much similar way to go about this, but as I struggled with it, I knew the long way was an option and one I could understand and complete).
### The process:
In Atom text, I created a new file and paste the URLs into it; I then saved the file as urls.txt
Then I placed the url.txt file into my file called _wget-abbiebrightdiaries_
Following, I opened _New Terminal at Folder_ 
I then placed this at the terminal/command prompt: $ wget -i urls.txt -r --no-parent -nd -w 2 --limit-rate=100k
And it worked! Wget was now able to retrieve the content of Abbie Bright’s diary from the web. 

**Success!**
![](https://user-images.githubusercontent.com/105247273/174705505-f62e3e2a-7708-4e0e-8753-57b6566a9e12.png)

### Voyant:
When I attempted to place the file into Voyant, I was met with this error:

![](https://user-images.githubusercontent.com/105247273/174705586-365f7188-beb0-4c4b-8d2a-48be54a33d81.png)

At this moment, I began to worry. _How am I going to understand the contents of her diary without Voyant?_ I knew Voyant was such a sufficient tool to use for large works and texts. I was determined to figure this out. I was going to head to discord until I remembered how well Skyler Richards and I worked together in Part Three. I reached out and asked for some help and together we were able to discover how to place Bright’s diary into Voyant. First I switched Bright’s Diary on the website from viewing it by individual photos of her diary:
![](https://user-images.githubusercontent.com/105247273/174705665-f4461ef2-f883-4eb0-bef6-c10ec8c08e27.png)

To the text version: 
![](https://user-images.githubusercontent.com/105247273/174705728-99f33b9d-887c-44f2-8f8c-a283f23e53cc.png)


From here, I copied the URL of the text version and pasted it into Voyant. And _voila_:

![](https://user-images.githubusercontent.com/105247273/174705815-9098e81c-09fa-4ea6-95b4-206d92d15f5b.png)
**It worked!**

## Exploring Bright’s Diary Using Voyant:
### Common words:
Home 
Went
Came
Men 
Mr
Night 
Day 
### Observation of Common Words:
Common travel trends (came, went, home, day, night)
Patriarchy/Male dominance/Historical trend of male dominance 
Mostly uses words like men, Mr, brother, and boys, and a lack of female-based words like women, girls, and woman.

### Google Maps 
Working with Google Maps to articulate the West travels of Anne Bright was, in certain aspects, challenging. I started off looking through [Bright’s Diaries](http://www.kansasmemory.org/item/223662) using Voyant and [this](https://www.kshs.org/p/abbie-bright-papers/13986) source (which is the same website that Bright’s digital archives were retrieved) to find the timeline and location of her travels. After accumulating the data, I organized it using Google sheet, which I learned to use for the first time by referencing the example [Jack Dougherty and Ilya Ilyankou](https://handsondataviz.org/mymaps.html) provided within the _Point Map with Google Maps_ tutorial. Here is the Google Sheets i created:
![](https://user-images.githubusercontent.com/105247273/174705042-0f95a9ea-9e59-4c67-b851-87829a68469b.png)


However, when I uploaded the Google Sheet to Google Maps, I was unable to change the icon and colour of each location:
 ![](https://user-images.githubusercontent.com/105247273/174705943-70c2f4cc-7f69-4e65-8f33-2426026ca9f1.png)


I then made two separate sheets: one for Abbie’s home and schooling and another for her travelling. I uploaded each to the Google map, which worked!
![](https://user-images.githubusercontent.com/105247273/174706037-28cd3445-5917-4976-b303-50968abbd70c.png)


