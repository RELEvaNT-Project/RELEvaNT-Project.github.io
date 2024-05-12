---
layout: default
---

# Overview of the project

Reinforcement learning (RL), both classical algorithms and their deep variants, critically rely on the fact that the underlying system is assumed stationary, i.e., how the environment responds to the agent's actions does not vary with time. Unfortunately, many real-world problems fail to exhibit such stationary property. Therefore, to bring out the full potential of RL in complex application domains, existing methods must be extended to cope with non-stationarity in a principled way.

RELEvaNT investigates **new models and methods** for efficient deep RL in non-stationary environments and the potential applications on several "human-centered" domains. In particular, RELEvaNT investigates:

* Model-based RL in which the learned model _captures a low-dimensional factorized representation of the world_. We investigate the extent to which such low-dimensional representations enable the agent to robustly cope with changes in the dynamics of the world.

* _Meta-learning approaches to model-based RL_, in order to render the process of learning the low-dimensional models mentioned above more data-efficient. In particular, we build on existing frameworks for model-agnostic meta-learning to construct pre-trained "prototypical" representations that can then be adjusted, at interaction time, using a small number of samples, thus enabling the agent to adjust to changes in the environment.

The outcomes of the project will be evaluated in several real-world non-stationary domains, exploiting the application of RL in robot control and human-robot interaction.

# Research team



Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./another-page.html).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project.

# Header 1

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
