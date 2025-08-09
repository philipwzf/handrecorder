# handrecorder
A better interactive hand editor that can render and parse handviewer link (.lin also supported).

**TODO**
- [x] Get hands from acbl live
- [ ] Get hands from hand records
- [ ] Clicker to help record the plays

## Pair games with acbl live
For pair games with acbl live scores, we used a similar program as [acbl live converter](https://www.tameware.com/adam/bridge/utilities/) made by Adam W to get the handviewer links from the score page. On the scores page of acbl live (the page that displays all scores for a specific pair), ask your browser to View Source (Chrome, Edge) or Show Page Source (Safari). Then copy the entire source code page to the textbox to get a list of all the hands played.
## Get hands from hand records
Right now no good ideas for this except using chatgpt. should have an easy pdf parser that can split up the file into different boards so chatgpt can focus more easily.

## Clicker to help record the plays
Similar to bbo hand editor, we want to have a clicker (and show actively played cards) that will make it easier to record the played cards. Better than bbo hand editor, we want to live update the played card pase on the left such that the link can update as we go and we can change the numbers on the left directly rather than going back all the way by clicking previous.
