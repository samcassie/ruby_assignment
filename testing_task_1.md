### Testing task 1:

# Carry out static testing on the code below.
# Comment on any errors that you see below.
```ruby

class CardGame

# no initialize

  def checkforAce(card)
    if card.value = 1
##### should be two equals
      return true
    else
      return false
    end
  end

  dif highest_card(card1 card2)
##### should be def not dif, and comma is missing
  if card1.value > card2.value
    return card
##### should be card1
  else
    return card2
  end
end
##### dont need a second end, and fix indentation of first
end

def self.cards_total(cards)
  total
#####total needs to be assigned a value or null
  for card in cards
    total += card.value
##### the end below should be placed here
    return "You have a total of" + total
##### total must be converted to a string
  end
end

##### missing an end for the class
```
