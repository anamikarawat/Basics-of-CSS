# Basics-of-CSS
# What is CSS?
![Screenshot (1826)](https://user-images.githubusercontent.com/95397876/177945857-b288c53b-9359-44f2-af0a-7e1dfac68d94.png)

# CSS Units
![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/177946028-8fa3c528-4101-4b7b-82bf-fad8741df4a6.png)

em ex ch rem lh vw vh vmin vmax
![Screenshot (1851)](https://user-images.githubusercontent.com/95397876/177946903-52f6290c-60b4-48d8-967e-38c94c19fbc9.png)

# Flexbox
![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/177946588-99708902-196d-4119-a715-7d976fa1bd6b.png)

# Layout modes before Flexbox
1. Block- for sections in a webpage
2. Inline- for text
3. Table- for Two dimensional table data
4. Positioned- for explicit position of an element

# Why Flexbox?
1. A lot of flexibility
2. arrange items
3. spacing
4. alignment
5. order of items

# Terminology
1. Flex Container
2. Flex Items
![Screenshot (1826)](https://user-images.githubusercontent.com/95397876/177948399-8f895352-f8de-453b-aa25-d002847b035a.png)

# Flexbox axes
![Screenshot (1826)](https://user-images.githubusercontent.com/95397876/177948649-21ad15a9-5a6f-4362-804e-63e17169ac85.png)

# Terminology
![Screenshot (1826)](https://user-images.githubusercontent.com/95397876/177948995-98d417a8-3372-44a3-ba94-657c63f4e185.png)

# Flex Container Properties
1. display - create either a block level or inline level flex container i.e.-> flex , inline-flex
2. flex-direction - sets the direction of the main axis i.e.-> row , row-reverse , column , column-reverse
3. flex-wrap- Control the wrapping of flex items within the container i.e.-> nowrap , wrap , wrap-reverse 
4. flex-flow - shorthand for flex direction and flex wrap. i.e.-> flex-flow: <flex-direction> <flex-wrap>
5. column-gap- Specify the gap between columns using this. 
6. row-gap- Specify the gap between rows using this.
7. gap- Specify the gap between both row and column gap using gap: <row gap> <column gap>
  > values can be a non negative value or a % sign.
8. justify-content- Align items and distribute any extra spacing in the parent container. The alignment is always along the main axis. 
  i.e. ![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/177951893-d9f6adfd-796d-4961-b572-b9c37cd5a280.png)

9. align-items - Align items along the cross axis. i.e.-> flex-start, flex-end, center , baseline , stretch(default)
10. align-content - Align lines of content along the cross axis and distribute any extra spacing  in parent container. i.e.-> flex-start, flex-end, center , space-between , space-around , stretch(default)
  
  
  # Flex item properties
  1. order
  2. flex-grow
  3. flex-shrink
  4. flex-basis
  5. flex
  6. align-self
  
  # Baseline
  ![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/177953489-7c286b75-dae3-4bbf-8e79-7e72801fa863.png)

  ![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179360893-df1b3ca0-cbc5-46e4-96fb-76cf3b776f94.png)

  ![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179360914-b963ff87-1d87-4d58-b920-2d10ed80199d.png)

# Flex-Basis
Set the initial size of a flex item. Pixels, percentages or relative units, Default value is auto.

![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179361089-562682b1-ca70-4f14-bcee-57e32dfbe296.png)

# Flex-Values
![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179361145-512b5e99-08f7-41cf-bdb0-5e1ce708e696.png)

# align-self
Align the items individually . values like auto , flex-start, flex-end , center and  . Overrides the align-items value of the flex container.

# CSS GRID
![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179361283-e74643f0-e828-4b53-a08a-a406f4f9f20a.png)

# Terminology
![Screenshot (1850)](https://user-images.githubusercontent.com/95397876/179361319-4149dde3-8cd7-47c6-a4c4-5b374c75a07a.png)

# Terminology contains
1. Grid line
2. Grid cell
3. Grid track
4. Grid Area

# Grid Container Properties
Display, grid-template-columns , grid-template-rows , grid-template , column-gap , row-gap , gap , justify-items , align-items ,place-items , justify- content , align-content , place-content , grid-auto-columns , grid-auto-rows , grid-auto-flow

# Display 
create either a block level or inline level grid container . (Grid , inline-grid)

![Screenshot (1886)](https://user-images.githubusercontent.com/95397876/179361607-8e77ea45-f63d-4836-8532-3992a307aa06.png)














  
  














