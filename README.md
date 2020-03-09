Title: French Immersion in the City of Vancouver

Here is my screenshot :

![alt text]( https://kwan27.github.io/lab2/Screen%20Shot%202020-03-09%20at%2012.03.45%20AM.png "Mapbox Screenshot")

Link to map: https://kwan27.github.io/lab2/mapbox-map-lab-Ver_4.0.html 

Peer Critique

Cormac Chui, and Vicky Jiang and I all collaborated and tried to create a filter but we were unsuccessful as per our code below. What we have learned is that we can accomplish a lot however, we were not able to integrate everything we wanted into our code. Our goal was to contribute to each other’s code but I have not heard back from them yet. 	

The resources I used was Mapbox JS and used their examples to integrate onto my code. Some include from mapbox that I integrated are “Animate map camera around a point” and “Display a popup on click.” I also tried to use the example “Filter features within a map view” in the example below but it does not work that well. 

I did ask Vicky for some feedback on my map. Here is what she had to say:

“I like everything but I think that you could change the symbol of the schools to be more representative. Additionally, the 360 is cool, but I think that he might not love it because it doesn't really benefit your map.”

I have included these changes on my final map. I have learned that I need to create a map that is useful for the user and creating a map that circles around cannot be easily used to navigate. 

I also reached out to Katherine Song so that I can create a filter. One layer for elementary schools and one layer for high schools. I was unable to complete this either since I was unable to upload my point data for my schools to mapbox and create a url similar to this: mapbox://styles/mapbox/XXXXXXXXX.


Reflective Analysis:

This map was designed for parents who plan to enroll their children to French Immersion schools in the city of Vancouver. This map attempts to address the issues surrounding accessibility of French programs for students. In the city of Vancouver, there are only three elementary schools and thirteen high schools that offer the French immersion program. Furthermore, accessibility to these programs is rather difficult. According to the map, there are approximately one French immersion school per dissemination area. This map successfully communicates this to the map user by displaying only the relevant schools. The process I followed in the design of my map involve gathering the dissemination area and school data from the city of Vancouver website. The dissemination area was uploaded to mapbox. The school data was later edited manually to only show the relevant schools with French programs. All external links, paragraph spacing and titles were added so that the map can be more stylistic. The code was later added using a few examples from Mapbox JS. The city name and point of interests were removed from the map as it was deemed redundant. Only community areas are displayed with their respective boundaries. 

Using a computer or their tablet, this map is designed to allow parents to explore and navigate the neighbourhood of the nearest school and to explore and learn more about the school’s history, background, and culture through a small popup window. Links to websites are provided conveniently for parents without having to search online. This map was created to be cartographically pleasing for map users of a specific demographic to simplify navigation of the couple dozen schools in Vancouver and to limit the research that parents need to conduct. Some ways this map can be improved is to have a working search/filter function at the top. Schools that successfully get searched will appear with a popup window with a small checkmark or an X to indicate whether the school offers the program. A sample of my working code is < https://kwan27.github.io/lab2/mapbox-map-lab-Ver_2.6_CAN_FILTER.html >. The search function sort of works. I was able to filter schools using two or three letters, but I was unable to incorporate this onto the map I have submitted. I would set the street labels to appear only after a zoom of 15 has been achieved. I could have turned this layer off. In this case, I have decided to leave it on as it can be useful for parents to navigate around the neighbourhood. 







