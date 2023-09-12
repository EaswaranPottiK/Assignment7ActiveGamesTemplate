# index.html

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/c416af24-55eb-4e47-b929-f1cf64d8cb72)

!doctype defines that html code is written here

html lang = en specify language used here is english

meta charset defines the encoding used, in this case its utf 8

meta name and content ensure consistancy of view in mobile and desktop

title is the text displayed on tab, here the text written is - Document

html is lined to css via the link tag; href specify the location of doucument and rel specify the relationship - in this case it is stylesheet 

here we also import font from google using link, href and rel

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/ee0bf7d9-ff7e-40a5-9108-eecaeb3cc4be)

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/e3f89ff5-e017-48d9-a0dd-43f300095291)


here i have divided main div (class name main) into 2 div with class names left and right 

on left(div) consist of divs with class names photo item and joystick

image is imported using image tag img

heading tag h3 is used to put name of the person 

paragraph tag p is used to put a  discription of the image 

The divs with class item consists of an image and a heading to that image 

in the div joystick a para and an image is put side by side using flex; the text is allocated 33% of the space while images take up 66% of the space 

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/6a35f7fb-6c4f-46c3-a679-9bcdfda93e8a)

the right div consist of a heading div (rHeading) and multiple same cards div

rHeading provides an h1 heading tag with an input text field for white thick underline (input type = text)

each div with class=card consists of an image with a heading with h2 and a disciption using p tag

div with class name progress is used to put progress bar (by providing length and width via css

the percentage written on extreme right is made bigger by using inline style property font-size:bigger


# style.css

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/3db20ef8-a0e8-41c5-8d00-5fcdcabe8cd5)

border and padding are set 0 so that elements dont take any extra space than what is alloted

box sizing is set to border box so that elements does not exceed alloted space 

liner gradient is used to provide a trasition of background color; 180 degree means from top to bottom style must be applied 

height and width are set auto so that page size adjust as per requirements

here i have also font color and font famile (poppins)

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/d5407b0b-5fa8-40e5-8d48-3238038ae724)

dispaly flex is used so as to use flexbox

flex:1 specify the fraction in which left div must grow. Suppose left flext is 1 and right flex is 4 and if the screen size is 100cms. Than left portion will occupy 25 cms

height is given as 100% of screen

flex direction is specifed as coloumn so items will get arranged from top to bottom 

align items: so that each items is aliged in the center 

justify content is the spacing propery used here

border radius is used to make sharp corder of rectangle as rounded

padding is the spacing from element to its border ; here i have specifed only top and bottom padding (left and right are set to 0)

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/58bf0c5d-6d2f-49a0-9299-559378774da1)

1 rem = font size; the default font size is 16px

the rest of property have already been defined 

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/a081c8b4-cd8d-49e9-a866-f028d9456ec4)

line 55 states that css should be applied to input tag which is child of div with class rHeading

box shadow is used to apply a shadow to element : here x direction , y direction and shadow is specified 

![image](https://github.com/EaswaranPottiK/Assignment7ActiveGamesTemplate/assets/38095510/8c5ac10d-bee1-483b-ba6b-835034c6c06b)

line no 80 specify that css should be applied to div with class progress which is child of div with class card 

here border is defined as none to remove border of the box



























