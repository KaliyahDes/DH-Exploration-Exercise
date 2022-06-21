### DH Exploration Exercise Log

Name: Kaliyah Desormeaux 
Date: June 15th, 2022
Archive (the foundation of the DH Exploration Exercise: [Abby Bright’s Diary](http://www.kansasmemory.org/item/223662)

## Starting Stage of Using Wget

I began working with Wget to retrieve the content of [Abbie Bright’s Diray](http://www.kansasmemory.org/item/223662) from [this](https://www.kansasmemory.org/item/223662) webpage. 
I then started following the _Basic Usage_ directions in the [Wget tutorial](https://craftingdh.netlify.app/tutorials/wget/). 

And that didn’t work:
![](https://keep.google.com/u/0/media/v2/1uSZ2R7HO9fAPrxDr-21wpFpZFWQdzgNznnii84tYngtL2nqwnfD2pJqPIeZrJRo/15OEk7q3AeR7unC-uSX0JuYnMh5gpDodUcStP9TsDQPbKRfW7p71pLCCkZLzKWbU?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)

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
![](https://keep.google.com/u/0/media/v2/18huex8x_eSxTKV4d8qzRmMz0iEIkITQbWpZxkiYi0Nj1sn0HlxzooBwuOOhd8A/11GV9qFgpPHhgCJkarzK-hcZIYZ1WujVnf8W6QCUv6dSU1wRuCkHSC_Z2v0mt2jk?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)

### Voyant:
When I attempted to place the file into Voyant, I was met with this error:

![](https://keep.google.com/u/0/media/v2/1j8a8KcUVkKADhijsKhOj1J3T655cY0lFx72JGXWg0ZW-aG_gDC347LNvN6fwtjc/1--t2UsN1ugnGKLwDeVu1xAKoZTLcdfyVBzPBTzvTrDSJnot_xGeLjVrFnJKX?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)

At this moment, I began to worry. _How am I going to understand the contents of her diary without Voyant?_ I knew Voyant was such a sufficient tool to use for large works and texts. I was determined to figure this out. I was going to head to discord until I remembered how well Skyler Richards and I worked together in Part Three. I reached out and asked for some help and together we were able to discover how to place Bright’s diary into Voyant. First I switched Bright’s Diary on the website from viewing it by individual photos of her diary:

![](https://keep.google.com/u/0/media/v2/1AA4l-BRqu7VNeWUSJMwrWrB7vR3dTZR0pXb9H4giN1dNEp4SlNDtvuTu670U_hA/1cieQPvDgEkG9FRAyRYP8cCfQy5IoynoNR5wEujWaURzFKY7h3aiooALKUZmda0M?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)


To the text version: 
![](https://keep.google.com/u/0/media/v2/11CXExGhX54-uxFcFN4wy2giYBJVj0MiiF000BGsjAjbfqpo3MYVvPkaasJmgF94/1vXfnjxhRqw8GxEhYzBSbit6swvZjMIX61SBUbK6aDwhckxnhYIpYqLsRfyXB?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)


From here, I copied the URL of the text version and pasted it into Voyant. And _voila_:

![](https://keep.google.com/u/0/media/v2/1QiC-Q6uwgXYh85Oii2dSZhH9MqlgUqY0vVTD7ahDpouTU3ACFbN1J-me7zkzIzc/1sRZK_biM63L99jFnkDla_7W9DTo3GFedvaPwkNFB0h9rhK8Zzoxhqn-aKyGm5Q?sz=512&accept=image%2Fgif%2Cimage%2Fjpeg%2Cimage%2Fjpg%2Cimage%2Fpng%2Cimage%2Fwebp)
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
Working with Google Maps to articulate the West travels of Anne Bright was, in certain aspects, challenging. I started off looking through [Bright’s Diaries](http://www.kansasmemory.org/item/223662) using Voyant and [this](https://www.kshs.org/p/abbie-bright-papers/13986) source (which is the same website that Bright’s digital archives were retrieved) to find the timeline and location of her travels. After accumulating the data, I organized it using Google sheet, which I learned to use for the first time by referencing the example []() provided within the _Point Map with Google Maps_ tutorial. Here is the Google Sheets i created:


However, when I uploaded the Google Sheet to Google Maps, I was unable to change the icon and colour of each location:
 

I then made two separate sheets: one for Abbie’s home and schooling and another for her travelling. I uploaded each to the Google map, which worked!


Then I changed the icon and colour to fit the designated category: 


