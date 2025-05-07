# URBNC3 - Custom Footwear Technology

![Foot Model](imgs/foot_model.png) ![Sole Design](imgs/sole_model.png)
*Images will be uploaded shortly*

[Urbnc3](https://urbnc3.com/) is a startup focusing on customized supportive foot wear, I am a Co-Founder of.

Normal shoes have flat insoles - the same for everyone. Now when is the last time you met someone with the same foot as you? Never.
All feet are different and most of them would need individual support. In the past this was not possible, as individual adaptation required huge efforts and time of experts. With Urbnc3 this changed. We combine AI reconstruction with heuristic algorithms and 3d-Printing to offer the right support for every foot!

We have a specialized suit of products:

**Private Customers**:
- custom sandals 
- custom insoles

**Business Customers**:
(API is a fancy word for access)
- API access to our scanning algorithm.
- API access to our 3d-footmodel to insole algorithm.
- The combination of both.


## May contribution

### The Tech-stack 
Each pair designed by hand from the foot model took 4-5 hours prior to my algorithm. The algorithm I developed generates precise, anatomically accurate models in 1.5-2.5 seconds on a standard laptop. That is an improvent by about 4 orders of magnitude, or 10'000 times faster.

In the process of this I built:
- A custom 3D object library because existing solutions weren't good enough
- Mesh processing algorithms that maintain precision while being lightning fast
- Automated piplines
- APIs
- and much more

### Real Results

- From 4-5 hours to 1.5-2.5 seconds per pair
- Better anatomical accuracy than traditional methods
- More comfortable than the orthopedic insoles I've tried
- Currently being tested with real customers
