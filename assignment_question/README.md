# Assignment for State Management

## 1. Scrollable Widget
   - Create a widget that allows scrolling any direction (as you want).
   - Inside this widget, include:
     1. A list of Fibonacci numbers, ensuring it contains at least the first 40 Fibonacci numbers.

## 2. Display Widget
   - Each Fibonacci number in the list should be displayed alongside:
     - The number itself (e.g., 0, 1, 1, 2, 3, 5, ...).
     - A symbol or icon representing the type associated with that Fibonacci number (e.g., square, cross, circle).

## 3. Tap Functionality
   - Implement tap functionality for the numbers displayed in the widget:
     - Upon tapping a number:
       - Display a BottomSheet containing a list of items, filtered to show only items with the same type as the tapped Fibonacci number.
       - Each item in the BottomSheet should be tappable.
       - When tapping an item:
         - Remove the item from the BottomSheet and add it back to the main list.
         - Close the BottomSheet.
         - Highlight the item that was just added back in the main list.
         - Scroll to the Highlight item.
## 
**_Bonus if you have done this without third-party libraries._**         


# These are examples (it might takes some times to load GIF)

## Example of Diaplay list fibonacci
![](display_list_of_fib.gif)

## Example of added item only the same type
![](add_same_type.gif)

## Example of When scrolling to highlighted one when showing modal
![](scroll_to_highlighted.gif)

## Example of what to do when pop
![](pop_bottom_sheet.gif)

