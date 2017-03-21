# SUMMARY

In Canada we have single-payer healthcare. Under this model, basic services are provided by private doctors 
and the entire fee is paid for by the government (mostly the provincial government). Although most services 
are free at point-of-use, there are several services that are not covered. These services are typically paid 
for by private insurance companies, or out of the patient's own pocket.
This visualization shows how the public sector (i.e. provincial taxes) and the private sector (i.e. private 
insurance companies) spends money. 

# DESIGN

I chose a stacked area chart because it's a good way of visualizing distributions and I wanted to see changes
over time. I used colour as a visual encoding for different categories of spending. I also added labels.

However, I think it can be hard to determine an individual category's changes over time when it is stacked 
so I also wanted to add the ability to just see the area graph for one category of healthcare spending. 

I also added the ability to just look at one category and see how much of it is funded publicy and how much 
is funded privately. 

# FEEDBACK

__Justin Lockhat-Valverde__:
Add labels when choosing one layer so you remember which one you clicked. 

__Reponse__:
I added the label as well as buttons to show previous, next, and show all buttons


__Casey Iannone__:
What do you notice in the visualization?
- Nice viz & lots of data to comb through. 
- looks like public dollars are spend more on physicians & hospitals and private is spent on specialist 
    & drugs
- also looks like drugs are making up bigger chunks for public and private

Do you have any questions about the data?
- Everything is straight forward and simple. I would find a better position for the labels, as when 
    something is very small overlaps into others areas.

What relationships do you notice?
- Looks like were medicating more 
- also looks like drugs are making up bigger chunks for public and private

What do you think is the main takeaway from this visualization?
-public and private dollars are spent different
- drugs are eating up a larger chunk of dollars spent.

Is there something you don’t understand?
- nope.﻿

__Response__:
I think Casey's statement that we might be medicating more is an interesting one and one that I 
think is probably true. 


__Dave Lu__:
Maybe include where you got the data from

__Reponse__:
I included link for data


__Michael Adarna__:
It would be cool to add a third axis to see the dollar amounts

__Reponse__: 
I'm not sure how I would go about doing this right now but I agree this would be a good idea. 


__John Enyeart__:
I like it. The borders/outlines of different graph sections look a little bit choppy, though.﻿

__Response__:
At first I thought this might be because the path itself was jagged from lack of data points. But I 
tried removing crisp edges style and it seemed to help


__Michael Persinger__:
I don't like the colours.
Border that appears when hovering over layer is clipped by other path and appears to be jagged.

What do you notice in the visualization?
- The top part of the path stroke that shows on hover is clipped by the path above it.

Do you have any questions about the data?
- It would be nice if each category was defined, as is I don't necessarily know what is covered.

What relationships do you notice?
 - Facilities seem to cost less but medicine costs more.  

What do you think is the main takeaway from this visualization?
 - Private and public sectors spend their money very differently, probably to cater to different niches.

Is there something you don’t understand?
 - Why do you see different names for some of the categories when you view them by themselves (by 
    clicking on them). For example, "Other Professionals" becomes "Dental, Vision Care, Other".

__Reponse__:
I don't think there is a fix for the SVG border for now. It looks like there may be in the future: 
https://svgwg.org/specs/strokes/#SpecifyingStrokeAlignment 

I added better descriptions for layer labelling

I changed the colours


__Conrad Crofts__:
Might be good to show a grid to better see detail in data
Why leave in public health if it's 100% publically funded?

__Response__:
I think the grid would make it too cluttered so I won't add in any lines. 
I did think about omitting public health but I didn't for consistency. 


__Lisa Li__:
Maybe you can reference which tab to look at when you talk about some of the concepts

__Reponse__:
I think this is a good idea. I added some comments.


# RESOURCES

http://flowingdata.com/2016/01/05/causes-of-death/
https://bl.ocks.org/mbostock/3885211
