# This is a `<h1>` heading

This is a sentence. This is a sentence. This is a sentence. [This is an internal link](/terms "This is a custom title"). This is a sentence. This is a sentence. This is a sentence. This is a sentence.

This is a sentence. This is a sentence. This is a sentence. [This is an external link](https://new001-null.github.io).<br> This is a sentence. This is a sentence. This is a sentence. This is a sentence.

## This is a `<h2>` heading

This is a sentence. This is a sentence. This is a sentence. [This is an external link](https://new001-null.github.io).<br> This is a sentence. This is a sentence. This is a sentence. This is a sentence.

> “Your time is limited, so don't waste it living someone else's life. Don't be trapped by dogma – which is living with the results of other people's thinking.”
>
> ― Steve Jobs

This is a sentence. This is a sentence. This is a sentence. [This is an external link](https://new001-null.github.io).<br> This is a sentence. This is a sentence. This is a sentence. This is a sentence.

> Blockquotes can contain multiple paragraphs. Add a `>` on the blank lines between the paragraphs.
>
> > Blockquotes can be nested. Add a `> >` in front of the paragraph you want to nest.

This is a sentence. This is a sentence. This is a sentence. [This is an external link](https://new001-null.github.io).<br> This is a sentence. This is a sentence. This is a sentence. This is a sentence.

### This is a `<h3>` heading

`This is code.` **This is bold.** _This is italic._ **_This is bold & italic._** ~~This is strikethrough.~~ <mark>This is highlighted.</mark>

- this is a list item `<li>` of a list
- this is a list item `<li>` of a list
  - this is a list item `<li>` of a list
  - this is a list item `<li>` of a list
    - this is a list item `<li>` of a list
    - this is a list item `<li>` of a list
  - this is a list item `<li>` of a list
  - this is a list item `<li>` of a list
- this is a list item `<li>` of a list
- this is a list item `<li>` of a list

1. this is a list item `<li>` of a list
2. this is a list item `<li>` of a list
   1. this is a list item `<li>` of a list
   2. this is a list item `<li>` of a list
      1. this is a list item `<li>` of a list
      2. this is a list item `<li>` of a list
   3. this is a list item `<li>` of a list
   4. this is a list item `<li>` of a list
3. this is a list item `<li>` of a list
4. this is a list item `<li>` of a list

- this is a list item `<li>` of a list
- this is a list item `<li>` of a list
  1. this is a list item `<li>` of a list
  2. this is a list item `<li>` of a list
     - this is a list item `<li>` of a list
     - this is a list item `<li>` of a list
  3. this is a list item `<li>` of a list
  4. this is a list item `<li>` of a list
- this is a list item `<li>` of a list
- this is a list item `<li>` of a list

1. this is a list item `<li>` of a list
2. this is a list item `<li>` of a list
   - this is a list item `<li>` of a list
   - this is a list item `<li>` of a list
     1. this is a list item `<li>` of a list
     2. this is a list item `<li>` of a list
   - this is a list item `<li>` of a list
   - this is a list item `<li>` of a list
3. this is a list item `<li>` of a list
4. this is a list item `<li>` of a list

- [x] checklist item one
- [ ] checklist item two
- [ ] checklist item three

---

### Some Code Snippet

```js
import React, { StrictMode } from "react";
import { render } from "react-dom";
import { BrowserRouter as Router, Switch, Route } from "react-router-dom";
import { Home, Resource } from "./component";
import { registerSW } from "./lib";
import "./index.css";

// this is a comment

var bool = true;
let num = 100;
let str = "string";
const arr = ["a", "b", "c"];
const obj = {
  one: 1,
  two: 2,
};

const App = () => {
  return (
    <StrictMode>
      <Router>
        <Switch>
          <Route exact path="/">
            <Home />
          </Route>
          <Route exact path="/:directory/:subdirectory?">
            <Resource setMenu={setMenu} setPath={setPath} setUser={setUser} />
          </Route>
        </Switch>
      </Router>
    </StrictMode>
  );
};

render(<App />, document.getElementById("root"));
registerSW();
```

---

### Media

This is a large image:

![alt text here](https://new001-null.github.io/media/large.png)

This is a small image:

![alt text here](https://new001-null.github.io/media/small.png)

This is a tall image:

![alt text here](https://new001-null.github.io/media/tall.png)

This is a wide image:

![alt text here](https://new001-null.github.io/media/wide.png)

This is a large vector graphic:

![alt text here](https://new001-null.github.io/media/large.svg)

This is a small vector graphic:

![alt text here](https://new001-null.github.io/media/small.svg)

This is a tall vector graphic:

![alt text here](https://new001-null.github.io/media/tall.svg)

This is a wide vector graphic:

![alt text here](https://new001-null.github.io/media/wide.svg)

This is an animated graphic:

![alt text here](https://new001-null.github.io/media/animated.gif "This is a custom title")

This is an audio file:

<audio controls controlsList="nodownload" src="https://new001-null.github.io/media/audio.mp3"></audio>

This is a landscape video file:

<video controls controlsList="nodownload" src="https://new001-null.github.io/media/landscape.mp4"></video>

This is a portrait video file:

<video autoplay loop muted src="https://new001-null.github.io/media/portrait.mp4"></video>

---

### Tables

The first row is always the header followed by an extra line with dashes "-" and optional colons ":" for forcing column alignment.

| left-aligned |    centered    | right-aligned |
| ------------ | :------------: | ------------: |
| row 1        |   some text    |          1000 |
| row 2        | some more text |           100 |
| row 3        |   some text    |            10 |
| row 4        | some more text |             1 |

The first row is always the header followed by an extra line with dashes "-" and optional colons ":" for forcing column alignment.

| left-aligned |     centered     |      centered      |    centered    |    centered    | right-aligned | right-aligned |
| ------------ | :--------------: | :----------------: | :------------: | :------------: | ------------: | ------------: |
| row 1        | `const a = "a"`  |   **some text**    |   some text    |   some text    |        `1000` |          1000 |
| row 2        | `const b = "b"`  | **some more text** | some more text | some more text |         `100` |           100 |
| row 3        |   _some text_    |  `const c = "c"`   |   some text    |   some text    |          `10` |            10 |
| row 4        | _some more text_ |  `const d = "d"`   | some more text | some more text |           `1` |            10 |

---

### Test Exceptions

[missing href]()

[ ](/missing-text)

[invalid protocol](http://new001-null.github.io)

[internal](/settings)

[internal](https://omfg.env-staging.dev/settings?code=1234&source=abc)

[external (new001-null.github.io)](https://new001-null.github.io)

<a href="https://new001-null.github.io" referrerpolicy="origin">external</a>

https://new001-null.github.io

hello@env-staging.dev

![missing src]()

![invalid protocol](http://new001-null.github.io/media/small.png)

<img alt="valid image" src="https://new001-null.github.io/media/small.png" referrerpolicy="origin" align="right">

<video controls controlsList="nodownload" src="http://new001-null.github.io/media/landscape.mp4"></video>

- <input placeholder="Enter some text" />
- <input type="text" placeholder="Enter some text" />
- [x] checklist item 1
- [ ] checklist item 2
- [ ] checklist item 3

### XSS

<a href="javascript:alert('XSS')">Click Me</a>

<script>alert('XSS!')</script>

---

### Test `#` tags

#fyi #ask-me#no ##no

no#no #-no #0-no

http://new001-null.github.io/#no #data-is-beautiful https://new001-null.github.io/#no

[#link](https://new001-null.github.io/#no) #news [ #link](https://new001-null.github.io/#no)

![#image](https://new001-null.github.io/#no.png) ![ #image](https://new001-null.github.io/#no.png)

<p>This is a sentence. <a href="https://new001-null.github.io/#no"> #link</a> #politics <a href="https://new001-null.github.io/#no"> #link</a> This is a sentence.</p>

<img alt=" #image" src="https://new001-null.github.io/#no.png">

<video controlslist="nodownload" controls="" src="https://new001-null.github.io/#no.mp4"></video>

```
#no
#no
#no
```

<pre><code>#no
#no
#no
</code></pre>

Tags: #art, #data-is-beautiful, #wallstreet_bets, and #web.dev.

---

### Test `@` tags

@staff @eren-yeager@no @@no

no@no @-no @0-no

http://new001-null.github.io/@no @armin-a https://new001-null.github.io/@no

[@link](https://new001-null.github.io/@no) @mikasa [ @link](https://new001-null.github.io/@no)

![@image](https://new001-null.github.io/@no.png) ![ @image](https://new001-null.github.io/@no.png)

<p>This is a sentence. <a href="https://new001-null.github.io/@no"> @link</a> @historia-reiss <a href="https://new001-null.github.io/@no"> @link</a> This is a sentence.</p>

<img alt=" @image" src="https://new001-null.github.io/@no.png">

<video controlslist="nodownload" controls="" src="https://new001-null.github.io/@no.mp4"></video>

```
@no
@no
@no
```

<pre><code>@no
@no
@no
</code></pre>

Tags: @zek3, @hange-zoe, @annie_leonhart, and @reiner.b.
