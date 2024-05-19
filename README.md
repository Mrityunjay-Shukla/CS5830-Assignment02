# CS5830-Assignment02
Task 1 and Task 2 have been done on same code file


## Performance of API model on custom inputs
All the images were generated using MS Paint. I tried to keep the inputs varying in size and colour to test the model's real-world performance.

| Sr No.    |  Digit (Image) | Actual Class | Predicted Class |
|---------|--------------|:-----------------:|:--------------------:|:----------------------:|
| 1       | <img src="digits/digit_0.png"  />   | 0  | 2    |
| 2       | <img src="digits/digit_1.png"  />   | 1  | 9    |
| 3       | <img src="digits/digit_2.png"  />   | 2  | 5    |
| 4       | <img src="digits/digit_3.png"  />   | 3  | 8    |
| 5       | <img src="digits/digit_4.png"  />   | 4  | 3    |
| 6       | <img src="digits/digit_5.png"  />   | 5  | 8    |
| 7       | <img src="digits/digit_6.png"  />   | 6  | 8    |
| 8       | <img src="digits/digit_7.png"  />   | 7  | 8    |
| 9       | <img src="digits/digit_8.png" />    | 8  | 8    |
| 10       | <img src="digits/digit_9.png"  />  | 9  | 8    |

We observe that the model's performance is suboptimal. This issue can be attributed to the absence of image transformations during training. Additionally, the model encounters difficulties with varying input shapes, and almost no image exists in the original input size of (28,28).
