# JetPackCompose_Day-1

## setContent Block 

The activity's layout where composable functions are called. Composable functions can only be called from other composable functions.

## @Preview 

This annotation lets you preview your composable functions without having to build and install the app to an Android device or emulator.

## Column 

This function lets you arrange elements vertically

## Row 

This function lets you arrange elements horizontally

## modifiers 

This allow you to change the composable's size, layout, appearance or add high-level interactions, such as making an element clickable

Spacer(modifier = Modifier.width(8.dp)) This is used for providing Space between elements.

## LazyColumn and LazyRow

These composables render only the elements that are visible on screen, so they are designed to be very efficient for long lists.

  ### remember 
	
	Composable functions can store local state in memory by using remember, and track changes to the value passed to mutableStateOf .

  By using Compose’s state APIs like remember and mutableStateOf, any changes to state automatically update the UI. This is called recomposition.

  ### rememberSaveable 
	
	It is used to restore your UI state after an activity or process is recreated. rememberSaveable retains state across recompositions.It also retains state    	 across activity and process recreation.
	
	![WhatsApp Image 2022-08-28 at 7 41 11 PM](https://user-images.githubusercontent.com/11208646/187078673-14c3cdf5-1375-4f33-9038-71f6cfaf72fe.jpeg)
	![WhatsApp Image 2022-08-28 at 7 41 11 PM-2](https://user-images.githubusercontent.com/11208646/187078681-6d8cfd8f-4836-4760-a5a7-9223f3b080c2.jpeg)
