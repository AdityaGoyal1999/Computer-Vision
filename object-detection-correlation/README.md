## Object Detection with Normalized Cross Correlation

The dimensions of the person and the image are the same so the person can be detected easily with normalized cross correlation. After running the function, max point will correspond to the location of the person.

The following equation is used for Normalized Cross Correlation

$$ R(x,y)= \frac{ \sum*{x',y'} (T'(x',y') \cdot I'(x+x',y+y')) }{ \sqrt{\sum*{x',y'}T'(x',y')^2 \cdot \sum\_{x',y'} I'(x+x',y+y')^2} }$$
