How to center an element with display: grid

The "display: grid" property simplifies how to center an element. However, it is necessary to understand that the 
property "display: grid" needs to be applied to the parent container in order to center an element inside of it.
Here’s a step-by-step guide:
1. Create a parent container: It will receive the "display: grid" property.
2. Create a element inside the container: The element that is intended to be centralized.
3. Center the element: Use "place-items: center" to center items both horizontally and vertically.

"Place-items: center": This property is a shorthand for "align-items: center" and "justify-items: center",
which center the child elements both vertically and horizontally.

I have created a div parent and div child inside of it. I styled the div child in a circle format. I used 
"display: grid" in the div parent and "place-items: center" in the div child. A weird behavier happened when 
I created two paragrphs - the div child left the center and because of those other elements. So, I applied
"position: absolute" to the paragrphs to remove them from the normal document flow and don't disturb the div child 
behavier.
