# Personal Portfolio 🎨

This portfolio was designed and built as a reflection of how I approach software development: **intentionally**, **thoughtfully**, and with **attention to detail**. Rather than focusing on flashy effects or excessive tooling, my goal was to create a calm, cohesive experience that communicates both technical skill and design sensibility. ✨

This project provided me an opportunity to build something with AI assistance. Check out my [AI Usage Document](https://docs.google.com/document/d/1Re8Rdkl2V2f2mJLfRuaojURsSi7pBuw9VfKIY9h7PLY/edit?usp=sharing) to see how I used AI on this project.

## About Me 👋

I'm currently studying at **The Marcy Lab School**, a college alternative, as part of their **Software Engineering Fellowship**. Prior to Marcy, I studied **Political Science** and **Finance** at Saint Peter's University. 🎓

My interdisciplinary background shapes how I approach software development — integrating **systems thinking**, **communication**, and **intentional design** into the way I write code. I'm motivated by building technology that is **thoughtful**, **human-centered**, and designed to make a meaningful impact over time. 💡

## Closing 🌱

This portfolio represents where I am now as a developer — **curious**, **intentional**, and **continuously learning**. It will continue to evolve as I grow, but the core philosophy will remain the same: **build with purpose**, **care**, and **design with people in mind**. 🚀

## Reflection Questions 💭

### Question 1 🤔

Share one technical concept that you developed greater mastery over in this project. Demonstrate how you understand that concept by sharing your mental model of the concept. Then, show how you used that concept in your project.

### Response 1 ✅

One technical concept I developed greater mastery over in this project was **how elements interact with their containers**, particularly when using **Flexbox** for layout. I learned to think of containers as systems that control the positioning and behavior of their children rather than styling elements in isolation.

My mental model for Flexbox is that the **parent element defines the rules** of alignment, spacing, and direction, while **child elements respond** to those rules. Instead of forcing elements into place with margins or positioning, I focused on configuring the container to naturally arrange its contents using properties like `display: flex`, `justify-content`, and `align-items`. 📦

I applied this concept throughout my project, especially in the **hero section** and **navigation layout**. For example, I used Flexbox to center content both vertically and horizontally within the hero and to space navigation links evenly within the nav container.

### Question 2 🤔

Choose one project requirement that you found challenging and are proud of implementing. Describe what made it challenging and how you were able to implement the requirement by walking through your code as succinctly as possible. Remember that your audience does not know your code nearly as well as you do so you'll have to break it down in a logical manner for them to quickly understand it.

### Response 2 ✅

One project requirement I found challenging was implementing the **navigation bar**. I wanted it to appear beneath the hero section, remain sticky on scroll, and feel visually subtle rather than harsh or distracting. 🎯

This was challenging because my initial approach placed the navigation **inside** the hero section, which prevented `position: sticky` from working correctly. Through research and experimentation, I learned that sticky positioning depends on the scroll context of its parent, so I restructured my HTML to move the navigation outside the hero while keeping it visually connected.

I also struggled with understanding **`z-index`** and how layering works in CSS. By testing different values and learning how z-index interacts with positioned elements, I was able to ensure the navigation stayed above other content while scrolling. This experience improved my understanding of layout flow and debugging complex CSS behavior. 🔧

### Question 3 🤔

How did you leverage AI to assist your development of this project?

### Response 3 ✅

I used AI as a development assistant to help me think through problems when I got stuck. Instead of asking for direct answers, I explained what I understood about the issue and where I was confused, which helped me debug more effectively and clarify my own thinking.

AI helped break problems down into smaller, manageable steps and pointed me toward helpful documentation and learning resources. This sped up my workflow and reinforced concepts I was already learning at The Marcy Lab School. Using AI this way supported my learning rather than replacing it, especially within a fast-paced, year-long program.
