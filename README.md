# interactive-video-data-extraction
A key approach to enhancing multimedia experiences, such as interactive video, involves extending functionality beyond the core media playback. This could entail associating custom data with interactive elements within the video and then using this data to trigger actions or interactions on the surrounding webpage or external systems. It also allows for richer, more dynamic experiences that bridge the gap between the video itself and the broader web environment. 

Vimeo is a good example: custom data can be added to interactive elements, such as hotspots and overlays (in the case of Vimeo Interactive, for example). After setting up a hotspot or button action, you can add custom payload data to include key-value pairs. This should be familiar territory for most devs, and comes in handy for adding extra tracking or dynamically exporting data from the media player. 

The following pattern illustrates how an interactive video in a webpage can make itself heard for hotspot clicks. When a hotspot is clicked, the code checks for custom payload data. If present, the code extracts its value, logs it to the console, and displays it directly on the page. The same approach could also be used to send the data to a server.


![image](https://github.com/user-attachments/assets/815cec49-f156-416d-834f-d915bee9a8cf)


