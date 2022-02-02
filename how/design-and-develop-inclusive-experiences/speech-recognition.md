# Speech Recognition Testing

## Common Issues Identified During Speech Recognition Testing
- Duplicate link or button labels on a page. Unique, descriptive links are vital for allowing a speech recognition user to interact with interactive components on your page with basic speech input commands. For example, if you have multiple click here or register now links on a page, those links will prevent a speech recognition user from accessing content in an efficient manner.
- Controls without visual text labels. This includes controls that use placeholder text rather than labels. Without these visual text labels, speech recognition users will need to revert to the numbered structure of the page, which is often less efficient and adds more time to interacting with a page.
- Hidden input text with no "show" toggle. For example, a password field on a login page that does not give the ability to show and hide the password text. This creates a barrier for people using speech to text as they can't determine if what they said was interrupted correctly by the speech recognition software and thus may have to enter the password several times before successfully entering the correct password.
- Visual labels that don’t match the accessible name of a control.  Those same controls have a programmatic name, also known as the [Accessible Name](https://www.w3.org/TR/accname-aam-1.1/). Users typically have a much better experience if the words and characters in the visible label of a control match or are contained within the accessible name. When these match, speech-input users can navigate by speaking the visible text labels of components, such as menus, links, and buttons, that appear on the screen.
- Modal dialogs and iframes not registered by the software. This is common with speech recognition when a modal dialog or iframe is not coded right. If you can't access either a modal dialog or an iframe with the show numbers feature on a Mac, you need to revisit the coding of that component. 

## Testing Resources
Please use the Safari browser when completing Voice Control testing.

- [Use Voice Control on a Mac](https://support.apple.com/guide/mac-help/control-your-mac-and-apps-using-voice-control-mh40719/mac)
- [Use Voice Control on your iPhone, iPad, or iPod touch](https://support.apple.com/en-us/HT210417)
