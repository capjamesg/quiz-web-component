# quiz-web-component

A HTML web component that embeds a quiz element on a web page.

This component is ideal for use in educational content to help readers reinforce their knowledge of the material.

## Demo

Here is a demo of the quiz web component:

https://github.com/capjamesg/quiz-web-component/assets/37276661/2baa40f2-5785-4f8e-8e8b-615e238e08a2

## Setup

To use this component, first clone this repository:

```
git clone https://github.com/capjamesg/quiz-web-component
cd quiz-web-component/
```

Copy the `quiz.js` file onto your own website.

Add the following code to theweb page where you want to use the component, before you want to use the component:

```html
<script src="./path/to/quiz.js"></script>
```

You can then add the component. To do so, add the following code:

```html
<quiz-element
  data-question="What is James' favourite Taylor Swift song?"
  option-1="Folklore"
  option-2="Midnights
  option-3="Evermore"
  option-4="1989"
  answer="1989"
  explain-1="Try again!"
  explain-2="Not quite!"
  explain-3="Almost!"
  explain-4="1989 is the best!">
</quiz-element>
```

Set:

- `data-question`: The question to show.
- `option-1`, `option-2`, etc.: The options. You can specify any number of options.
- `answer`: The correct answer.
- `explain-1`, `explain-2`, etc.: The explanations to show when an option is revealed.

## License

This project is licensed under an [MIT license](LICENSE).
