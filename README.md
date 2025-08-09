# handrecorder
A better interactive hand editor that can render and parse handviewer link (.lin also supported).

**TODO**
- [ ] Get hands from acbl live
- [ ] Get hands from hand records
- [ ] Clicker to help record the plays

## Pair games with acbl live
For pair games with acbl live scores, we can implement a similar program as [acbl live converter](https://www.tameware.com/adam/bridge/utilities/) made by adam W to get the handviewer links from the score page. Before this is done, we can use adam W to get the format for bridgewinner then adapt it for handviewer link

## Get hands from hand records
Right now no good ideas for this except using chatgpt. should have an easy pdf parser that can split up the file into different boards so chatgpt can focus more easily.

## Clicker to help record the plays
Similar to bbo hand editor, we want to have a clicker (and show actively played cards) that will make it easier to record the played cards. Better than bbo hand editor, we want to live update the played card pase on the left such that the link can update as we go and we can change the numbers on the left directly rather than going back all the way by clicking previous.
