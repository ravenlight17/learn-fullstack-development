Default Margins on Headings (h1 through h6)

By default, web browsers apply their own styles to HTML elements, including top and bottom margins for headings. This is part of the "user-agent stylesheet."
These default margins can vary slightly between browsers and often cause unwanted spacing issues, especially when headings are placed close to other elements.
The problem the instructor encountered (around 4:49:35) was that the default bottom margin of the h2 and the default top margin of the h3 were collapsing or combining, creating more space than desired.
How to Tackle Default Margins

The most common and effective way to manage these default margins is to reset or explicitly set them using CSS:

Set margin: 0;: You can explicitly set the margin property to 0 for headings to remove all default margins. This gives you a clean slate.
h2, h3 {
    margin: 0;
}
Apply Custom Margins: Once you've removed the defaults, you can then add custom margin-top and margin-bottom values (or shorthand margin) as needed to create the exact spacing you want for your design. The instructor did this by setting margin-bottom on the h2 to 10px (4:50:35; https://www.youtube.com/watch?v=LzMnsfqjzkA) to control the spacing between the h2 and the h3.
By taking control of the margins, you ensure consistent spacing across different browsers and achieve your desired layout precisely.