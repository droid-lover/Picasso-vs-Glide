# Picasso-vs-Glide
A comparison between these two strong lib



Hello Guys , As we use Picasso and Glide to load images and to do stuff like that and

Although it looks quite the same but in details Glide is designed far better since with doesn't accept only Context but also Activity and Fragment. Context will be automatically extracted from those things you throw in.

And the brilliant benefit from passing Activity/Fragment to Glide is: image loading would be integrated with Activity/Fragment's lifecycle for example, pause loading in Paused state and automatically resume on Resumed state. So I encourage you to pass the Activity or Fragment to Glide not just a Context if possible.

Same Features which both GLIDE and PICASSO have are :- (Image Resizing ,Center Cropping,Transforming,we can set the Placeholder and Error image etc.)

But What Glide has but Picasso doesn't ????

An ability to load GIF Animation to a simple ImageView is the most interesting feature of Glide. And yes, you can't do that with Picasso. this is the best thing in Glide over Picasso in my Opinion.

Sachin
