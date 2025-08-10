**### **New Card Animations** 🎨✨

This project showcases a responsive and interactive card component with a hover-triggered animation. The card's design includes a dual-color gradient border and a hidden content section that becomes visible on hover.

#### Features
* **Interactive Hover Effect:** 🤩 When a user hovers over the card, the main content image scales down and moves up, revealing a title, a creative profession subtitle, and a set of social media icons.
* **Vibrant Gradient:** 🌈 The card is framed by a background with a `linear-gradient` of `#03a9f4` and `#ff0058`, creating a distinct visual style. A blurred version of this gradient provides a glowing effect.
* **Hidden Content:** 🤫 A content block containing a title and social media links is initially hidden (`opacity: 0`) and slides up to become fully visible on hover.
* **Integrated Social Icons:** 📲 The content area includes a list of social media icons (Facebook, Twitter, LinkedIn, and Instagram) implemented using SVG paths directly in the HTML. These icons are styled to change color on hover.

#### How to Use
To use this card component, simply copy the HTML and CSS code into a single file named `index.html`. You can then open this file in any modern web browser to see the animation.

#### Customization
* **Dimensions:** 📐 Adjust the `width` and `height` properties of the `.card` class in the CSS to change the size of the component.
* **Colors:** 🎨 The gradient colors can be modified by changing the hex codes in the `.card::before` and `.card::after` CSS rules.
* **Text:** ✍️ The title and subtitle text can be changed by editing the `<p class="title">` element in the HTML.
* **Links:** 🔗 Update the `href` attributes of the `<a>` tags within the `<ul class="sci">` list to link to your own social media profiles.
* **Image:** 🖼️ Currently, the card uses a placeholder, but you can replace the `<img>` tag to display your own image.**
