# Open-Source-Data-Visualization
Open Source Data Visualization Music

## Description
My project is about the data visualization of open source music. I used three categories for the data visualization: MusicInterests, MusicListens and MusicDownloads. I have made a chart of these values of the songs. So for every category there is one graphic, based on values of different songs. The graphs look like a music wave. These data is from [FreeMusicArchive](http://freemusicarchive.org). I also made a combination of the three graphs in an animation. Here the values change between the three categories. The sound wave changes in shape as a result of the data.

## Graph
Music Interests
![musicinterests](https://cloud.githubusercontent.com/assets/21360973/26760269/4cbe0c16-4914-11e7-9b9e-e74992553c7e.png)

Music Listens
![musiclistens](https://cloud.githubusercontent.com/assets/21360973/26760289/f0815a60-4914-11e7-9d12-4022aad67016.png)


Music Downloads
![musicdownloads](https://cloud.githubusercontent.com/assets/21360973/26760302/0f81e8f8-4915-11e7-834f-70db1c5a9140.png)

## Animation
... image/animation 

## Source Information
### site 
The data is from [FreeMusicArchive](http://freemusicarchive.org)

### json file 
This is the link to the [json file](code/DM_tracks_data2.json) with the data I used.

## Code
This are the files with the code I used for the graphs. I made these graphs and animation in [plotdevice](http://plotdevice.io). The code to flatten the data is a python file. 
### Organize code
The code to [flatten](code/DM_flatten_track.py) your data. This means that you delete the information/data in the code that you don't need. You can choose which data you want. 
### Code graph 
This is the code for the [wave graph](code/DM_2-5-17_graph_wave). The code is used for the three categories [interests, listens and downloads]. You can do this by changing all the track_listens to track_interests or track_downloads. 
### Code animation 
This is the code for the [wave animation](code/DM_2-5-17_graph_wave_anim). 

## Sketch 
...
(link bestand) 
