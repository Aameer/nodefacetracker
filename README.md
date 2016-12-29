Node implementation for clmtrackr:
================================

![tracked face](http://auduno.github.com/clmtrackr/media/clmtrackr_03.jpg)

**clmtrackr** is a javascript library for fitting facial models to faces in videos or images. It currently is an implementation of *constrained local models* fitted by *regularized landmark mean-shift*, as described in [Jason M. Saragih's paper](http://dl.acm.org/citation.cfm?id=1938021). **clmtrackr** tracks a face and outputs the coordinate positions of the face model as an array, following the numbering of the model below:

[![facemodel_numbering](http://auduno.github.com/clmtrackr/media/facemodel_numbering_new_small.png)](http://auduno.github.com/clmtrackr/media/facemodel_numbering_new.png)

[More about clmtrackr](https://github.com/auduno/clmtrackr/blob/dev/README.md)

To run the test run.
`node index.js`
Then in your browser visit localhost:3000.
You will need to give permission for your webcam and press start.
Then give it a :smile: and see if detects it.

