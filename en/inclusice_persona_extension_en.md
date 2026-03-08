# Inclusive Persona Extension (Markdown Version)

---

## Visual Disabilities (Blindness)

### Barriers to using the Web

- Cannot see. Cannot understand the visual information.
- Cannot use the Web without the text-to-speech feature (or braille output) of a screen reader.
- Cannot use fingers or major pointing devices like a mouse to click or tap on items.

### Solutions

- Provide alternative text for images and icons.
- Provide alternative formats such as audio descriptions for video content.
- Use “real” text rather than images of text.
- Mark up heading structures and landmarks appropriately.
- Make all functionality operable through a keyboard.
- The link text and button label alone should convey the purpose of the link and button.
- Provide labels to identify form controls by using the <label> element.
- Make the data table structure as simple as possible and use the <th> element for table header cells.
- Use WAI-ARIA attributes and make sure a screen reader uesr is aware of dynamic context changes.
- Do not start playing any sounds automatically when the page is loaded.

---

## Visual Disabilities (Low Vision)

### Barriers to using the Web

-  Cannot see well enough.
    - Cannot see clearly (Blurred vision, Double vision)
    - Glare sensitivity
    - Flickering eyesight
    - Peripheral vision loss
    - Central vision loss
    - Wandering eye (Shaky vision)
-  People with low vision might need screen readers depending on the severity.

### Solutions

- Allow users to enlarge content on the screen.
- Use “real” text rather than images of text.
- Provide adequate contrast between foreground text and its background color combinations.
- Make all functionality operable through a keyboard.
- Make all keyboard-accessible components have a visible focus indicator.
- Make sure the information is transmitted correctly even if the color is changed to the opposite color by the user agent’s function.
- Allow users to use a custom style sheet.
- Layout content in chunks to better facilitate flow of information.
- Present headings to make it easier to understand the content overview.
- Follow familiar user interface design patterns.
- Do not change content with accidental triggers such as a mouseover or keyboard focus.
- Match the screen readers reading order with the visual layout.

---

## Color-Blindness / Grayscale Print

### Barriers to using the Web

- Difficulty distinguishing between certain kinds of colors.
    - Protanopia / Protanomaly (Low or insensitivity to the color red)
    - Deuteranopia / Deuteranomaly (Low or insensitivity to the color green)
    - Tritanopia / Tritanomaly (Low or insensitivity to the color blue)
    - Monochromacy
- When printing a web page in grayscale, color-dependent information cannot be identified correctly.
- When opening a web page with a monochrome e-reader, color-dependent information cannot be identified correctly.

### Solutions

- Do not rely on color alone to communicate information.
    - Add an underline to the link (especially one in a sentence).
    - Express the visual hierarchy of text using non-color elements such as font size and thickness.
    - In figures (graphs, etc.), shapes other than colors should also be used as clues for visual identification.
- Make content understandable / usable even when displaying it in grayscale.

---

## Auditory Disabilities / In a public

### Barriers to using the Web

- Hard of hearing or total loss of hearing.
- Can't make sound in a public place (transportation, library, etc.) including situations where the battery of Bluetooth headphones is dead, forgot to bring headphones, etc.

### Solutions

- Provide transcripts for audio content.
- Provide captions (subtitles) for video content with audio.

---

## Motor Disabilities

### Barriers to using the Web

- Cannot use fingers or major pointing devices like a mouse to click or tap on items. Need to rely on the following means:
    - Adaptive / Customizable keyboards
    - Mouth stick
    - Various switch devices (or buttons)
    - Speech recognition software
    - Eye-controlled input devices
    - etc.
- Difficult to freely change the device orientation.

### Solutions

- Make all functionality operable through a keyboard.
- Make all keyboard-accessible components have a visible focus indicator.
- Make links, buttons, etc. large enough to be able to click / tap / execute without the need to perform precise pointing operations.
- Describe the labels of links and buttons clearly to support voice input. Write in text and mark up appropriately.
- Make sure that the page functions properly when the device is used in either "portrait" or "landscape" mode.

---

## Cognitive / Learning Disabilities

### Barriers to using the Web

- Difficult to recognize or memorize information.
- Easily distracted by sights and sounds in their environment.
- Difficult to read text (such as Dyslexia).

### Solutions

- Follow familiar user interface design patterns.
- Avoid interactions that cause unexpected changes.
- Avoid interactions that rely on the user's memory.
- Use clear and plain language when presenting text-based information.
- Present headings to make it easier to understand the content overview.
- Use visual elements (images, figures, icons, symbols, etc.) to make content understandable without reading.
- Allow users a way to adjust the time or turn off the time limit if the content provides a time limit.
- Movement or blinking in the content should be limited within 5 seconds or allowed to be stopped by the user.
- Do not use flashes that flash 3 times or more per second in content expression.
- Do not start playing video and audio content automatically when the page is loaded.
- Use legible fonts.
- Make the font size and line spacing large enough to improve readability.
- Provide multiple means of contact. (e.g. text chat as well as phone calls)

---

## Aging

## Barriers to using the Web

- Difficult to use fingers or major pointing devices like a mouse precisely to click or tap on small items.
- Hard to read small and light text (Presbyopia).
- Hard of Hearing.
- Difficult to recognize information and hard to remember things.

### Solutions

- Make links, buttons, etc. large enough to be able to click / tap / execute without the need to perform precise pointing operations.
- Provide adequate contrast between foreground text and its background color combinations.
- Use “real” text rather than images of text.
- Make the font size and line spacing large enough to improve readability.
- Follow familiar user interface design patterns.
- Avoid interactions that cause unexpected changes.
- Avoid interactions that rely on the user's memory.
- Use clear and plain language when presenting text-based information.
- Present headings to make it easier to understand the content overview.

---

## Mobile

### Barriers to using the Web

- The field of view for obtaining information is narrow due to the small screen.
- Size of text tends to be small and difficult to read.
- When used outside, the content is difficult to see due to the glare of natural light.
- Since it is tapped on with a finger, precise pointing is difficult compared to using a mouse.
- Typing is more troublesome than using a hardware keyboard.
- Mouse-based interactions (such as mouseovers) are not available.

### Solutions

- Clarify content priorities from a user experience perspective and structure information serially based on those priorities.
- Make the font size and line spacing large enough to improve readability.
- Allow users to enlarge content on the screen.
- Provide adequate contrast between foreground text and its background color combinations.
- Make links, buttons, etc. large enough to be able to tap without the need to perform precise pointing operations.
- Minimize the frequency of text input (typing).
- Do not implement mouseover-dependent interactions.
- Do not change content with accidental down-event.

---
