## Style
- using camel case : e.g backgroundColor rather than background-color.
- cleaner to use StyleSheet.create

## Height and Width
- adding a fixed width and height to style
- pixels

### Flex Dimensions
- dynamically based on available space
- parent does not have either a fixed width and height or flex, the parent will have dimensions of 0 and the flex children will not be visible

## Layout with Flexbox
- Flexbox is designed to provide a consistent layout on different screen sizes
- normally use a combination of **flexDirection**, **alignItems**, and **justifyContent** to achieve the right layout

### Flex Direction
- flexDirection defaulting to column instead of row, and the flex parameter only supporting a single number

### Justify Content
- flex-start, center, flex-end, space-around, space-between and space-evenly

### Align Items
- flex-start, center, flex-end, and stretch

### Going Deeper

## Handling Text Input
- text changed : **onChangeText**
- text is submitted : **onSubmitEditing**

## Handling Touches
### Displaying a basic button
- **Button** provides a basic button component that is rendered nicely on all platforms
- render a blue label on iOS, and a blue rounded rectangle with white text on Android

### Touchables
- so you will need to do a bit of work to get them looking nicely in your app
- **TouchableHighlight** anywhere you would use a button or link on web
- **TouchableNativeFeedback** on Android to display ink surface reaction ripples
- **TouchableOpacity** can be used to provide feedback by reducing the opacity of the button, allowing the background to be seen through while the user is pressing down
- you don't want any feedback to be displayed, use **TouchableWithoutFeedback**

### Scrolling lists, swiping pages, and pinch-to-zoom

## Using a ScrollView
- you can scroll both vertically and horizontally (by setting the horizontal property)
- using swiping gestures by using the **pagingEnabled** props
- Set up the **maximumZoomScale** and **minimumZoomScale** props and your user will be able to use pinch and expand gestures to zoom in and out
- you have a long list of more items than can fit on the screen, you should use a **FlatList** instead

## Using List Views
- **FlatList** works well for long lists of data
- **FlatList** only renders elements that are currently showing on the screen, not all the elements at once
- **FlatList** component requires two props: **data** and **renderItem**
- **data** is the source of information for the list. 
- **renderItem** takes one item from the source and returns a formatted component to render
- data broken into logical sections : similar to UITableViews on iOS, then a **SectionList** is the way to go






