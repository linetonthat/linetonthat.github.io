---
title: "A Dataviz Poster"
date: 2022-09-07T11:59:37+02:00
draft: false
tags: ["meteor", "poster", "dataviz", "D3", "Gimp", "radial chart", "astronomy"]
---
## Designed to be printed
When I design personal data visualizations, I usually imagine them printed on paper, although they mostly remain in their digital format.
However, there are a few that I would like to see materialized. For example, I printed my sister's vegetable garden data visualization for her. In a way, it's a reminder of what she accomplished in the first year of her vegetable garden. It was easy to do, as it's A4 size (the visualization was done with PowerPoint).
![Text](/images/22-09_dataviz_Anne_vegetable_garden.png)

## Initial version in digital format
Earlier this year, I worked on a __[meteor shower calendar](https://public.tableau.com/app/profile/line.ton.that/viz/MeteoShowersRev1/Recap)__. This version was designed to be interactive, because of its format (intended to fit on a computer screen), where it is difficult to display all the names of the showers on the graph. You could list them on the side, as Michela Lazzaroni did in a __[data visualization](https://www.behance.net/gallery/75126385/Shooting-Stars-La-Lettura-347-dataviz)__ that inspired me a lot. But in my initial version, there wasn't much space, and I prefer to have the labels close to the associated visual cue to avoid back and forth eye movement.

<div class='tableauPlaceholder' id='viz1662546713716' style='position: relative'><noscript><a href='https:&#47;&#47;www.imo.net&#47;resources&#47;calendar&#47;'><img alt='Recap ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MeteoShowersRev1&#47;Recap&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='MeteoShowersRev1&#47;Recap' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Me&#47;MeteoShowersRev1&#47;Recap&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1662546713716');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1366px';vizElement.style.height='795px';} else { vizElement.style.width='100%';vizElement.style.height='1327px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>


## Turning it into a poster format
I had the idea of turning the data visualization into a poster, where I would have enough space to display all the origins of the showers, and I could hang it on my wall as a reminder about the date of the meteor showers. As I was considering a large poster size (A2 size), I realized that in order to get a good resolution, it would be too difficult for me to work directly from the existing data visualization in Tableau and change its size. I decided to use D3.js instead to build the whole poster and in particular to build the background color gradient (I had previously created it using a graphic editor).

## The new version
In this new version, I added the moon phases. This was part of my initial ideas, but I didn't have time to include it in the initial version. It became a top priority, after I painfully realized this summer that the full moon on the day of the Perseid's peak was not ideal :-/.
Due to time constraints, I was not able to build it entirely using D3.js. The final design was made with Gimp, to add the title, captions, explanations and credits.

Here is a preview of the poster (next year's data!):
![Text](/images/23-9_meteor_shower_calendar_poster.png)


You can find the high resolution version __[here](https://drive.proton.me/urls/YXBS6TJJRG#Vya9M8G6X0cm)__.
If you use it at home, I'd be happy to know :). Send me a message on __[Twitter](https://twitter.com/LineTonThat)__ or on __[LinkedIn](https://www.linkedin.com/in/linetonthat/)__.


Main data source: __[2023 Meteor Shower Calendar](https://www.imo.net/files/meteor-shower/cal2023.pdf)__ from the __[International Meteor Organization](https://www.imo.net/)__.
