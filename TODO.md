# TODO

## Little jobs

## Big jobs
- Are river levels/rainfall seasonal? How will I deal with that?

- Is it really sensible to make a single model for all the rivers? How about a single model for all the gauges on a single river? - Maybe the best way to test this is to just built models for both and see how well they do. Alternatively, could characterise the similarity in 'character' between gauges. How similar is the response to rainfall between gauges?

- Should I build very custom models making use of intuition about how rivers behave? Or should I make very general learnt models that attempt to make use of all the infomration available in its raw form? This decision is a matter of how much data is available. It will need to have more intuition embedded if insufficient data is available. How much is 'sufficient'? - I will have to built a model and find out!

- Generate autocorellegram to see how self-correlated the data is. Ie. how far back is it useful to use data from?

- Go and research what types of models seem appropriate. What do other people use to predict river levels, or time series in general?

- Incorporate DSM (height map information) to determine things like 
  - is this rainfall station in the catchement for this gauge? 
  - map out relatioships between gauges. eg. upstream/downstrea/subsidaries
  - characterise the gradient of the terrain between the rain and the gauge. How long will it take to rise?
  
- Need to address biased dataset. Most points will have low river level. 