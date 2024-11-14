# Prevent

This Prevent website is designed to be a simple introduction to the UK Government's Prevent
strategy. It was designed to be of assistance to any small charitable organisation so that
people running group discussions are aware of possible signs of radicalisation, even though it is
not a legal requirement for them to act upon them.
Note: This website was developed as part of a "boot camp" learning project, and one of the learning
objectives was to use AI in it's design / creation.

Note - I have run out of time to complete this section properly.

## Design

### Font
I have chosen the following font https://fonts.google.com/specimen/Kodchasan

#### Suggested Color Palette
I asked ChatGPT for suggested colour scheme and it came up with this:
https://coolors.co/f5efe6-b4d0e7-a8d5ba-333333-f2a488
##### Warm Beige (#F5EFE6):
Use as the background color for a welcoming, calming feel.
Represents warmth and approachability.
##### Soft Blue (#B4D0E7):
Use for headers and key informational areas to create a sense of trust and reliability.
Soft blues are often perceived as safe and stable, making it easier to present potentially sensitive information.
##### Gentle Green (#A8D5BA):
Use for action buttons and highlights to symbolize growth, support, and safety.
Green also conveys community and well-being, aligning well with the group’s focus.
##### Dark Charcoal (#333333):
Use for text to ensure readability and contrast against the lighter background.
Dark charcoal is easier on the eyes than black, providing a softer feel while still being readable.
##### Warm Coral (#F2A488):
Use sparingly for accents and call-to-action sections where attention is needed, such as reporting concerns or highlighting key points.
Coral is friendly and approachable and can help make the site feel more lively and engaging.
##### White (#FFFFFF):
For sections with a lot of text or card backgrounds to maintain a clean and uncluttered look.
Sample Application
Background: Warm Beige for the entire page background, to convey approachability.
Headers and Section Titles: Soft Blue, to make titles stand out in a friendly, calming way.
Buttons: Gentle Green for actions like "Report Concerns" or "Learn More."
Accent Elements: Warm Coral to emphasize certain elements, like icons or call-to-action text.
Text: Dark Charcoal to keep everything readable and accessible.
##### Why This Palette Fits Your Goals
This color scheme is calming, welcoming, and subtle, which aligns well with the purpose of
educating and creating awareness without appearing overly formal or alarming. Additionally, 
these colors are associated with safety, stability, and growth, which reinforce the group’s 
values and the purpose of the Prevent strategy.

## Layout

Wireframe <https://www.figma.com/design/QxpaSyZvgtB34CZAvvcuvI/Figma-basics?node-id=1669-162202&t=hkeutaOBfdGWxEAj-1>

the current version:

![multi-mockup](assets/images/Screenshot%20from%202024-11-13%2013-48-00.png)


## Credits

text: the vast majority of the text is taken verbatim from the Home Office website, from the following course https://www.support-people-susceptible-to-radicalisation.service.gov.uk/portal#awareness-course

Images:
Photo by <a href="https://unsplash.com/@robertbye?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Robert Bye</a> on <a href="https://unsplash.com/photos/group-of-people-gathering-on-field-4hcpIbqQM8c?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash">Unsplash</a>


## Use of AI

I used AI throughout, sometimes positively, and sometimes not so much.
I employed both external ChatGPT, and also the VSCode built-in CoPilot.

The Project Plan was created using ChatGPT - this seems to have been quite effective.
For the html / css itself AI was very hit and miss.
In particular CoPilot could be quite unhelpful.
I've found it asks if you want to accept code, but it's made some additional "changes" to what you select.
So - I got into the habit of doing Cntl-Z until it undid anything I didn't recall back to my last change,
which I'd then reinstate with a Cntl-Y
I also suspect AI somewhere down the line "broke" a bit of my navbar's functionality.
The collapsed version currently no-longer collapses after following a link.

## Testing

### HTML validation

![HTML Validation](assets/images/Screenshot%20from%202024-11-13%2013-16-57.png)

### CSS validation

![css Validation](assets/images/Screenshot%20from%202024-11-13%2013-20-12.png)

### Lighthouse scores
- basically I need to make the image even smaller (I've already reduced it twice)

![Lighthouse](assets/images/Screenshot%20from%202024-11-13%2013-40-15.png)

### Deployment

Deployed using Github Pages


