# Manual Visual Reviews during Accessibility Testing

The following reviews can only be done through a visual review of content and won't be flagged by an automated testing tool.

## Check that videos and audio clips are accessible
- All videos should have both accurate and punctuated closed captions as well as a transcript. Note that if  an interactive transcript has been implemented, you should still include a non-interactive transcript for the deaf-blind community and for anyone that does not wish to interact with the video.
- All audio clips should have a transcript.

## Confirm interactive components are properly styled
- All links should be underlined by default. If not, the CSS needs to be changed to a:link {text-decoration: none;} 
- Check that interactive components (buttons, links, cards, menu items) have a visual change when you tab and on hover.

## Confirm content and visualizations do not rely on color alone
- Look for any content that has been called out with a color such as red. Ensure that the importance of that content has been conveyed through bolding it.
- Look for data visualizations that are conveying content through color alone. Ensure meaning is conveyed through other means such as shapes or patterns.

## Test your site with images shut off
Confirm that a site design renders well when you shut off images in your browser settings. There are people in the neurodiverse community that shut off images to avoid triggers.
