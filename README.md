# Tribute Page

---

First of five freeCodeCamp web programming projects to earn a Responsive Web Design certification.

---

## The Subject

I have chosen Elon Musk for my attribute page. For me, Elon Musk is one of the biggest visionary entrepenuor of our times. I remember thinking ten years ago about how will be impossible for an electric car to be as powerful as a petrol one (I was wrong). Today, I believe in his Neuralink project and, in a way, I see it as the future of the smartphone.

Building this page I came to realize the early age at which Elon Musk started into the web development world and, should be a clear example for us as a society to nurture technologically our young generation for a brighter future.

## The Development

The main focus of this project was about HTML semantic, responsive image, and the use of selectors in the CSS file.

At the end of this project, I am aware of the importance of HTML semantic and, some rules discovered on the way, such as header and footer can not be nested in the main tag. Apart from that, accessibility plays a key role being a must using enough contrast, meaningful names, and access keys for our links.

When it comes to CSS I found that we can reach the same result using different approaches. For instance: we can center or elements in the body tag (since the page is mostly aligned center) or set them up individually in each section of our project.

### Image Responsive

This was the most challenging part since I wanted to explore two solutions that could pass the freeCodeCamp test, this [article](https://www.freecodecamp.org/news/how-to-center-anything-with-css-align-a-div-text-and-more/ 'How to Center Anything with CSS - Align a Div, Text, and More') helped me.

Solution 1

```css
#image {
  max-width: 100%;
  height: auto;
  display: block;
  margin: 0 auto;
}
```

Solution 2

```css
#img-div {
  display: flex;
  justify-content: center;
  flex-direction: column;
}
#image {
  max-width: 100%;
  height: auto;
  margin: 0 auto;
}
```

Despite both work, I will stick with the first solution. Short and cleanest for what we need here!
