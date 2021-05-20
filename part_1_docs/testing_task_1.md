### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.

Note that we are only looking for errors here.

**Not** any issues with, i.e.: 
Thinking that methods should be renamed or should be class level, or using string interpolation etc.

These aren't errors but rather standards that vary from developer to developer.

Only comment on errors that would stop the tests running.

```python

# Beginning from here

class CardGame:

  def check_for_ace(self, card):
    # Single equal sign (=) is an assignment operator. This should instead be a double equal sign (==) comparison operator 
    if card.value = 1:
      return True
    # Else needs to be closed with a colon (:)
    else
      return False
   
  # Mis-spelling of def as dif
  # Comma needed to separate card1 and card2
  dif highest_card(self, card1 card2):
  # This if/else statement does not include logic for a draw scenario
  if card1.value > card2.value:
    # no variable called card (should read card1)
    return card
  else:
    return card2

# Not indented correctly
def cards_total(self, cards):
  # Total variable is not assigned
  total
  for card in cards:
    total += card.value
    # Return statement also indented incorrectly (should be outside of loop)
    # Total is an integer which cannot be concatenated to a string in this manner
    return "You have a total of" + total
  
```
