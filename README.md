#Functionality:
“Add an item” area functionality:
  Adding an item to a column
    -[x] The user enters an item in the text box
    -[x] The user selects a column from the drop box
    -[x] The user clicks items “Add Item” and the item is added to the correct column
    -[x] Deleting an item
    -[x] The user clicks the “x” by an item and it is removed from the column
  Searching
    -[x] As the user enters text in the search box, both columns are filtered to display only items matching the text entered thus far
    -[x] The page should be responsive 
    -[x] There is no mockup for responsive, use your intuition here

Requirements:
  -[x] To submit your answer, please send us a link to a github repo
  -[x] Please use React.js for Javascript functionality
  -[x] Please use a CSS framework of your choice 
  -[ ]The page should be SEO friendly 

Optional (not required but very much appreciated):
  Use local storage to persist the entered items in the browser
  Use Compass to generate your CSS
  Be creative and come up with extra features to earn more points; if you do so please let us know what exactly you added there

COMMENTS:
# In order to be SEO friendly, this application needs to be ran by the server first using Isomorphic techonology (pre-render)
# using localStorage API canpersist the entered items (Don't have enough time to sort the data structure out), possible solutioin may be that:
  two key:value pairs, first one is column1:[{value:'ITEM'},{value:'ITEM'},...], second one is column2:[{value:'ITEM'},{value:'ITEM'},...]. 
  Construct a getLocalStorage() and a setLocalStorage(), this.state.item1 = getLocalStorage(column1), this state.item1 = getLocalStorage(column2),
  use setLocalStorage to set State.