 ### How can we ensure that each card is received once and only once?
Assuming a large population will be using the index card data exchange protocol, it's important to think of a long-term solution that will work when scaled. First, we should closely examine a few points that will help us narrow down the various way we can check for duplicates.

In class we explore a few possibilities that could solve the issue of duplication, the first of which is index card acknowledgement. By requiring confirmation of the note card delivery from person to person, this ensures the card is being passed around continuously. Furthermore, it is now much easier to count how many times a card has already been passed around.

Another important part of the icdep is being able to send a complete message over the span of several note cards. For this reason, by adding a count to each card we can establish the message order and ensure there is only one of each index card (e.g. card 2 out of 3).
