- Only one Coachmark + TeachingBubble combo should be displayed at a time
- Coachmarks can be stand alone or sequential. Sequential Coachmarks should be used sparingly, to walk through complex multi-step interactions. It is recommended that a sequence of Coachmarks does not exceed 3 steps.
- Coachmarks are designed to only hold TeachingBubbles
- Provide descriptive text in the `ariaDescribedByText` prop to let accessibility impaired users know how to open/access the Coachmark with keyboard controls. (See example in documentation)
- The keyboard shortcut for opening the Coachmark is `Alt + C`
- Consider when the Coachmark loads on-screen: the default value `delayBeforeCoachmarkAnimation` is set to 0, but you can increase this number to delay when the coachmark is displayed. Adding a delay can make the Coachmark stand out more, so consider scenario needs and page load times when adjusting this number. A delay that's 2-4 seconds is recommended if you choose to use one.