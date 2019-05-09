
# Talk @ Data Visualization Lisboa
### Vega - a declarative visualization language for everyone, even machines
[Meetup](https://www.meetup.com/Data-Visualization-Lisboa/events/258866318/)
You have ventured into D3.js and found a world of flexibility and unlimited creation, however you end up focusing on events callbacks and the details of Canvas and SVG for longer than anticipated. Or maybe you don’t even want to learn Javascript but crave the expressiveness of D3? If you're working on standalone plots, Vega might be the solution! Built on top of D3 itself, Vega is defined as a visualization grammar. It allows us to declare not only a visualization’s design but also its dataflow and interaction in a JSON format that you can take anywhere! This JSON generates web-based views using Canvas or SVG, and can even be integrated in a wide array of platforms such as Flourish, Kibana or Power BI. In this talk we’ll learn how to use the building blocks of Vega to unleash its potential to create almost any visualization we can think of. We will also take a sneak peek at how automated visualization design systems are also embracing Vega

### How to run the code
The live code done during the talk can be found in the `/code` folder. 
The finished Vega specification for each step of the tutorial are in `/code/specs`. 
To run each example just edit `index.html` and edit `spec` to be the path to the Vega specification you want to run.
```javascript
    20| const spec = "specs/01_strip_plot.vl.json"
```
To quickly launch the sketchpad run the following command inside the `/code` folder
```
    python3 -m http.server
```

### References
This talk was heavily inspired by the talks [Reactive Building Blocks Interactive Visualizations with Vega](https://www.youtube.com/watch?v=Y8Fp9z-9DWc) by Arvind Satyanarayan and [Vega Lite: A Grammar of Interactive Graphics](https://www.youtube.com/watch?v=9uaHRWj04D4) by  Krist Wongsuphasawat, Dominik Moritz, and Arvind Satyanarayan.