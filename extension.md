## How can we add additional features to the protocol without breaking previous functionality?

### Send to any individual on the whole UW campus
In addition to the unique id of each card, we can also add the student id or the name of the recipient so each person knows whether this card is meant for them.

### Specify whether contents are ASCII text, Unicode text, or binary values
To classify the types of messages, we can use different colors on the card, or other shapes so the recipient will know whether the contents are ASCII text, Unicode text, or binary values before seeing it 

### Keep a record of what nodes the card has passed through.
Each node can be assigned a unique id, and the card can have a routing field that contains the nodes' id so that when the card passes through the nodes, the nodes will add their id in the routing field. Each node can also determine if this card is duplicated or has previously passed through their node by checking the id in the routing field.
