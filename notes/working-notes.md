# Working notes

### Sun, Mar 27
- No exact loss function is specified. Close match is said to be F1 Macro.
- Instead of going for a softmax (multi-class), we are sticking to sigmoid in the final layer. Why? Multiple birds can be present in the final layer!
- A modified F1 Macro can be constructed. In the first iteration I could not implement it. Some neat coding is required.
- A rough EDA is done but more R&D is required.
- Currently only spectogram is incorporated. CNN models can be fitted on the time components of the audio to diversify our models.
