# FCC — Product Landing Page
This is another FreeCodeCamp *Responsive Web Design* project.

## User Stories
User Story #1: My product landing page should have a header element.
User Story #2: I can see an image within the header element. A company logo would make a good image here.
User Story #3: Within the #header element I can see a nav element.
User Story #4: I can see at least three clickable elements inside the nav element, each with class nav-link.
User Story #5: When I click a .nav-link button in the nav element, I am taken to the corresponding section of the landing page.
User Story #6: I can watch an embedded product video.
User Story #7: My landing page has a form element.
User Story #8: Within the form, there is an input field where I can enter an email address.
User Story #9: The #email input field should have placeholder text to let the user know what the field is for.
User Story #10: The #email input field uses HTML5 validation to confirm that the entered text is an email address.
User Story #11: Within the form, there is a submit input.
User Story #12: When I click the #submit element, the email is submitted to a static page with the mock URL: https://www.freecodecamp.com/email-submit
User Story #13: The navbar should always be at the top of the viewport.


# What I'm Learning
After a bit of research, I'm seeing that div tags shouldn't be used as liberally as I thought. Instead, semantic tags that define structure more specifically are better.

A media query is a CSS technique that uses the @media rule to include a block of CSS properties iff a certain condition is true.

I'm doing a bit of research to make sure, but it seems we don't really need to use media queries. Maybe rarely, but as I understand it they were originally for creating responsive design, and flexbox and grid already seem to do that now, in a better way.

Back in the day, media queries were used for targeting specific device sizes, when there were only about 4. Now it's nigh-impossible to target individual devices anymore. Instead, add breakpoints where your design breaks.

Say you start with your design for small devices such as phones. As you drag your browser window wider, when do the lines become too long to read comfortably? When could you make better use of the screen? This is the point at which to add a Media Query and write some additional CSS for larger screens.

This way, devices under that breakpoint get the narrow layout, and anything over it gets the layout using more horizontal screen space.

One rather brilliant alternative way to use media queries is to change the CSS based on the type of pointer being used. Is it a coarse pointer, indicating a touchscreen, or is it a fine pointer, indicating a mouse? This might be the best way to distinguish.

Grid systems should use CSS Grid. Many places where we find using Flexbox unwieldy are where we should use Grid.

Flex containers are treated as blocks by the rest of the page.