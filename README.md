Title: French Immersion programs in the City of Vancouver

Here is my screenshot :

![alt text]( https://kwan27.github.io/lab2/Screen%20Shot%202020-03-09%20at%2012.03.45%20AM.png "Mapbox Screenshot")

Link to map: https://kwan27.github.io/lab2/mapbox-map-lab-Ver_4.0.html 

Peer Critique

Cormac Chui, and Vicky Jiang and I all collaborated and attempted to create a search filter but we were unsuccessful. What we have learned is that we can accomplish a lot however, we were not able to integrate everything we wanted into our code. Our goal was to contribute to each other’s code over the weekend once one of us successfully creates a filter but no one was able to do that successfully. A sample of my code is below. 

Mapbox JS was a resource I used a number of times. I tried my best to integrate their examples onto my code. Some include from mapbox that I integrated are “Animate map camera around a point” and “Display a popup on click.” I also tried to use the example “Filter features within a map view” in the example below but it does not work that well. 

I did ask Vicky for some feedback on my map. Here is what she had to say:

“I like everything but I think that you could change the symbol of the schools to be more representative. Additionally, the 360 is cool, but I think that he might not love it because it doesn't really benefit your map.”

I have included these changes on my final map. After Vicky’s feedback, I have learned that I need to create a map that is useful for the user. Creating a map that circles around a point is not useful nor easily navigatable. 

I also reached out to Katherine Song so that I can create a filter. I tried to create a layer for elementary schools and one layer for high schools. I was unable to complete this either since I was unable to upload my point data for my schools to mapbox and create a url similar to this: mapbox://styles/mapbox/XXXXXXXXX.


Reflective Analysis:

This map was designed for parents who plan to enroll their children to French Immersion schools in the city of Vancouver. This map attempts to address the lack of the French Immersion program for students in the city of Vancouver. Currently, there are only three elementary schools and thirteen high schools that offer the French immersion program. According to the map, there are approximately one French immersion school per dissemination area meaning access to these programs is rather difficult. The process I followed in the design of my map involve gathering the dissemination area and school data from the city of Vancouver website. The dissemination area was uploaded to mapbox. The school data was later edited manually to only show the relevant schools with French programs along with their address, school name, and website. All external links, paragraph spacing and titles were styled to create a cartographic effect. The code was later added using a few examples from Mapbox JS. The city name and point of interests were removed from the map as it was deemed redundant. Only community areas are displayed with their respective boundaries. This helps parents easily navigate to the nearest school that offer French Immersion. 

Using a computer or their tablet, this map is designed to allow parents to explore and navigate the neighbourhood of the nearest school and to explore and learn more about the school’s history, background, and culture through a small popup window. Links to websites are provided conveniently for parents without having to search online. This map was created to be cartographically pleasing for map users of a specific demographic to simplify navigation of the couple dozen schools in Vancouver and to limit the research that parents need to conduct. Some ways this map can be improved is to have a working search/filter function at the top. Schools that successfully get searched will appear with a popup window with a small checkmark or an X to indicate whether the school offers the program. A sample of my working code is < https://kwan27.github.io/lab2/mapbox-map-lab-Ver_2.6_CAN_FILTER.html >. The search function sort of works. I was able to filter some schools using about two or three letters, but I was unable to incorporate this onto the map I have submitted above. To make this map better, I would set the street labels to appear only after a zoom of 15 has been achieved. I could have turned this layer off. In this case, I have decided to leave it on as it can be useful for parents to navigate around the neighbourhood. 







