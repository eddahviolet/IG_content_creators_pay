# IG_content_creators_pay
The main challenge with content creators is the lack of transparency in payments leading to novices getting under-paid. Here is a brief analysis of the payments Kenya Instagram content creators receive for Posts, Reels &amp; Static Posts and a linear regression to help them determine their lower limit in future pays

How much should you charge as an Instagram content creator in Kenya so that you do not under-price yourself? 

It takes a time and effort to build an audience on Instagram and start earning, so you should most definitely get your worth!!  However, the payments in content creation industry are hush hush. So how do novices without networks within the agencies, with other content creators, and within brands, to advise them, price their work accordingly? Well, Linear Regression to the rescue.

I did a brief analysis of the payments Kenya Instagram content creators receive for Posts, Reels & Static Posts and a linear regression to help them determine their lower limit in future pays. The models are not as sturdy as I would like the to be, but are good enough to be used as a guide of the least amount to accept.

The source of this data is Kenyan creators on Instagram. I used the data to make regression model that I then use to make input boxes in VBA to make it easy for ANYONE to use the model. 

The findings

Reels are the money maker. Brands are willing to pay more for them. 57% of total earning were from reels. (admittedly they do take more effort to make than static posts or stories) 29% from posts and 14% from stories.

A person can earn from content creation on Instagram with as low as 2,000 followers (this was the lowest follower count in the data set). The data set has a large range of 188,000 with the highest follower count being 190,000.

All the regression models have a low R- squared. For for reels it is 0.160797, for stories it is 0.0517527 and static post its is 0.383185. However this doesn’t mean they can’t be useful, they can be used as a guide. Whatever value one gets from the model should be multiplied by 3 and used as their lowest price limit before adding expenses and tax.

![Dashboard Instagram Content Creators Payment](https://user-images.githubusercontent.com/106580846/205642371-374ee23e-3d7c-4eaf-aa44-0b60fc8d787d.png)

How to use the models

I made input boxes in VBA using the regression model equations to make it easier for ANYONE to use the models to calculate the price of the each of the items.

Click on one of the three images depending on the which item you want to have the price calculated then enter your follower count in the input box. The price of reels, Instagram stories and static posts will appear in cells A1, A2, A3 respectively.

![vba prices](https://user-images.githubusercontent.com/106580846/205643452-5eb82523-5100-4c95-bcb9-71710413377c.png)

