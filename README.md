# Treat :Focus as a first class interaction
I will lead into this by stating that I am a person that plays video-games. A lot of video games. In fact it is my primary leisure activity and what this means that a large part of my interactions with technology are not mouse or touch based.

While some notable “mouse” style menus in games come to mind (Destiny, No Man’s Sky) nearly all games that utilize a controller rely on the concept of focus to make in game menus navigable.

Focus in a video game menu
When I use the word focus I am speaking to the visual representation of where the systems cursor rests at any given moment. Video games indicate your place within an interface by visually changing an element. Implementation varies wildly; from a simple arrow pointing at a selection to a drastic change in orientation, color, position, or size. A very important facet of focus in a video game is that the style persists. You can move your attention to another item or task and the interface continues to present where you left the cursor ready to press the button.

> Design focus to actively communicate where focus is

My opinion of a successful focus implementation in a video game menu is one that is not only distinct but one that continues to remind you where focus it. The busier an interface is the more important it becomes to provide consistent and obvious cues to help me reorient so that I can stay in control.

## Lack of focus in the browser
The browser is capable of doing what I just described. The browser has been capable of it since the 2000s. :hover and :focus were both made available in CSS2 but :hover has always been the first class citizen when it comes to design and implementation.

Many times in my career I have been told to remove default browser styling for focus states because they distracted from most carefully considered hover states. I am writing this in 2025 because I still see a lack of proper focus styling.

The more recent, and welcome, boom of concern around accessibility put focus back into the design conversation, but, it did not elevate it to the first-class heights of hover. While many systems and sites received focus updates the result was, and is, often a simple dotted outline around the element. Present, but flavorless.

## Persistent -active- focus
A dotted outline in many cases gets the job done, many users that rely on tab navigation in the browser know what it means but it begs the question “Where is your sense of style?”. It is likely that you or a team of designers agonized over hover and even active styles for your buttons and links, focus deserves that same attention.

Hovering is an active state. The user’s input device is moving, they are directly connected to the action. Focus is passive it stays where the user left it and will not change until it is updated.

To keep a user oriented on where focus lies, think like a game designer, and design focus to actively communicate where focus is.
