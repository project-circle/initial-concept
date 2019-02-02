# A document to store initial discussions

## UI (a bit early, but important)

- status updates / messages are broadcast to distinct groups of people
- interacting with a status update joins you into the 'chat'
  - if there are multiple people with the same first name in a chat, it will expand to show their last name, otherwise it will be first name only.
- conversations become read-only after 24 hours (time frame should probably be driven by user behaviour when this is demoed)
- Light theme and dark theme (prompted to select on app install)

## Friends

- New conversations can only include friends
- People in the conversation dont have to be friends with each other, just the person who started it. 
- Can see messages of non-friends in same conversation
- Adding friends works with friend requests like FB (two party approval)
- Friends can be added directly by email address (enter email, sends friend request to that user)
- Users can opt in to appear in name searches
- User can opt in to appear in friend suggestions (but these will be based on something e.g. same party, same gym. Not just, steve knows this guy)
- Can sort friends into groups, friends can be in multiple groups
- Somehow encourage groups based on subject (dota 2) and groups based on closeness (family, close friends etc)
  - when a friendship is created, each user should be given the option to choose which `groups` the person should be placed in to.
  - we can look to automate the `closeness` criteria based on number/frequency of interactions between two people.
- Unfriend no longer see conversations started by them. But can still see messages from them in conversations started by someone else.
- If someone is blocked you cant see messages from them or receive friend requests from them

## Profile

- Very minimal
  - Picture
  - First name 
  - last name
  - Email (defaults to private, can be shared with groups)
  - Phone number (defaults to private, can be shared with groups)

## Problems

- Conversation titles - When starting a conversation, the title (viewable by me) can be the name of the group so I know what its about. However when receiving conversations, what will the title appear as to me? Cant use the friends title and dont want to make them enter one. With no title, might be bad UI, to see what all your conversations are about. Auto tagging? or at least auto suggest tags on first open of conversation?
  - Essentially, how do we group similar conversations in a meaningful way.