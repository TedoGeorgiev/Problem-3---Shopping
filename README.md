# Problem-3---Shopping
# Create a program that lists stores and the items that can be found in them. 
# You will be receiving commands with the information you need until you get the "Go Shopping" command. There are three possible commands:
# •	"Add->{Store}->{Item},{Item1},…{ItemN}"
  o	Add the store and the items to your notepad.
  o	If the store already exists, just add the additional items which need to be bought from it.
  o	All items in the notepad should be unique! If an item is already added to your notepad, no matter in which store, do not add it.
# •	"Important->{Store}->{Item}"
  o	It is a major item which must be bought! So, you need to add the item at the top of the store's list.
  o	If the store does not exist, add it to your notepad along with the item. 
  o	If an item is already in your notepad, no matter in which store, do not add it.
# •	"Remove->{Store}"
  o	Remove the store and its items from your notepad if it exists.
  o	If an important item exists in the store's list, ignore the command.
# In the end, print the stores in the following format:
  "{store}:
    - {item1}
    - {item2}
  …
    - {itemN}"


