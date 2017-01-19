# Java-Web-Browser
Created using Java Swing
Using GUI elements such as textfield for address entry, JEditorPanes to display content of the websites and the history.

The program uses linkedlists to hold history. (Web addresses are saved in the linkedlists)
Two more linkedlists are used for forward and back function. 
-When the back button is hit, the current address is removed from the back linkedlist and added to the forward linkedlist, when foward 
  is hit, the opposite happens. The linkedlists are stacks, elements are added to the front and removed from the front of the list.

FileReader is used to store history in a textfile and browser setting prefences.
