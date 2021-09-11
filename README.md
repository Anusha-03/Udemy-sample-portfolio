# Udemy-sample-portfolio

UPDATING THIS README WITH SOME NOTES I TOOK...
GENERAL HACKS
windows + shift + S for taking SS
Codepen for HTSML CSS JS
DevDocs for documentation of tags in HTML
windows button + . for emojis in any text field
Use emojipedia to add little emojis or pictures if using online pictures 
Pesticide can be downloaded to show all the boxes (div elements) etc. and is useful for debugging of code

WEB DEV TIPS IN CODE:
prefer keeping your css properties in alphabetical order so that is easier to debug
ctrl + alt + F for beautifying the code

HEIRACHY 
order of preference of 
a) styles is:  inline css > css in <style> tag > external css field
b) selectors in css is: id selectors > tag selectors > normal selectors like body { } html { } etc


****Difference between ID and CLASS is that more than one tag/ element can have the same CLASS but only
one element in the whole code can have a particular ID  ALSO we can have more than one CLASS for the
same element but not more than one ID****

#####All HTML elements are static by default#####

@@@@@ Relative positioning is relative to the initial position of the element while absolute positioning is 
relative to the element's parent element's position @@@@@

$$$$$ Using px for font-size can be a bad idea as it changes from browser to browser so use % instead like
100% is 16px and use unitary method for your no of px $$$$$

%%%%% em used for font means the width of 1 capital M so em and % are two ways of expressing font-size which
would be same for all browsers
SO, 16px = 100% = 1em
using rem is most advantageous as it does not get affected by upstream root changes as all sub tags derive their
fonts from the main body tag if font is mentioned in the body tag %%%%%

&&&&&& by giving the paragraph a different id and using the clear: left; property to the para ID we can make
just the heading of the para to be inline with inserted image whereas the text continues being aligned 
normally &&&&&

***** CSS Button Generator is a site that can be used for generator the code to a stylistic button customized
for your site ****

