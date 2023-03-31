# Low-light-Image-Enhancemet
Implementing the Zero-Refernce Deep Curve Estimation model for low light and improving it further by introducing Dark Channel Prior(DCP) of image as spatial attention mechanism.  

The proposed method follows a spatial attention mechanism to emphasize appropriate regions.
![comparision_of_dcp](https://user-images.githubusercontent.com/119122797/228820010-f45cbfc9-c369-49c4-b030-8de8a403a939.jpg)
a)Ground Truth, b)Image Enhanced by original dcp model, c)Image Enhanced by our model.  

From above figure we can see that the our model enhances whiter/cloudy region appropraitely compared to orginal model,  which tends to overenhances the those region.

