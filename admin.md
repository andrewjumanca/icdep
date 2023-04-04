### How can we send commands ("SLEEP", "RESTART", "ARE-YOU-THERE", etc) to individual nodes in the network, rather than treat them as pass-through intermediaries?

Rules and proper administration is necessary in order for the ICDEP to work. Assuming every card sender follows their rules correctly, cards can be more effectively and safely transffered.
Here are a few rule sets which would be required in order to correctly administer potential protocol extensions:

#### Acknowledgement:
Each node acknowledges the transfer of the card handed to them. If the card is not to be recieved by that node and there is no other node closer than a node should not choose
to recieve that card. This ensures that messages are being circulated in an area that is closer to them and not as close to unaffiliated nodes.

#### External Feature Labeling:
The information described in features.md explains how adding additional information to the external section of the message (envelope, postcard, etc.) can increase efficiency without
sacrificing previous protocol behavior. By allowing each node (card passer) to vew only a fraction of each card information in a read-only way, this expands the protocol
without need for complete hardware change.
