#Version 0.1.1
## Bug fixes
- Fixed double children IDs insertion upon post edit (#63)

# Version 0.1.0
## Features
- Create a session to associate an external chain address to a Desmos address. 
- Create a post using a `MsgCreatePost` and providing a message. You can also decide whether other users can comment on such post or not. 
- Like a post using a `MsgLikePost` and specifying a post id. 
- Unlike a post using a `MsgUnlikePost` and specifying a post id.

## Notes
- When generating Desmos accounts, the path to use is `m'/852'/0'/0/0`
- The stake token denomination is `desmos`  