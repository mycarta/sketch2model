# sketch2model

This was a project from the [2015 Calgary Geoscience Hackathon] (http://www.agilegeoscience.com/blog/2015/5/15/canadian-codeshow) organized by [Agile Geoscience] (http://www.agilegeoscience.com/blog/2016/2/16/a-european-hackathon). You can read more on the hackathon in an Article on the September 2015 issue of the Canadain Society of Exploration Geophysicists journal Recorder: [Open Collaboration: Hackathons and Tomorrow’s Subsurface Software] (http://csegrecorder.com/articles/view/open-collaboration-hackathons-and-tomorrows-subsurface-software).

The original idea, proposed by [Elwyn] (https://github.com/scibbatical) at the Hackathon, was to make an app that would turn an image of geological sketch into a model:
![flow](https://raw.githubusercontent.com/mycarta/sketch2model/master/workflow.PNG)
 
The implementation of the finished app involves using morphological filtering and other image processing methods to enhance the sketch image and convert it into a model with discrete bodies, then pass it on to Agile's [modelr.io] (https://www.modelr.io/) to create a synthetic.

Blog posts:
[sketch2model] (https://mycarta.wordpress.com/2016/05/04/sketch2model)
[sketch2model – sketch image enhancements] (https://mycarta.wordpress.com/2016/05/25/sketch2model-sketch-image-enhancements)
[sketch2model – linking edges with mathematical morphology] (https://mycarta.wordpress.com/2016/07/22/sketch2model-linking-edges-with-mathematical-morphology)
