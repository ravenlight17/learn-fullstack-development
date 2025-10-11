Why did the instructor group the  h1, h2, h3, h4, p elements in the css to add the the text-shadow. Isnt that not DRY. Why didnt he put it in the body element? 

That's a great question about being DRY (Don't Repeat Yourself) in CSS!

The instructor grouped the h1, h2, h3, h4, p elements together to apply the text-shadow property because buttons do not inherit font families (as mentioned around 3:43:20). While text-shadow is not exactly font-family, similar inheritance rules apply to various text-related properties.

If the text-shadow were applied to the body element, not all elements (like buttons, which have their own default styles) would necessarily inherit it. By explicitly targeting h1, h2, h3, h4, and p using the group selector (h1, h2, h3, h4, p), the instructor ensures that only these specific text elements get the shadow, while still being concise and avoiding repetition compared to writing the rule for each element individually (4:25:39).

This approach allows for more control and predictable styling across different types of elements on the page.



