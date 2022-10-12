# Contextual Bandits : A Survey

<p>
<img src="./images/maxresdefault.jpg" width="500"/>
</p>

#### Problem Setting
<ul>
    <li> We have <img src="https://render.githubusercontent.com/render/math?math=K"> bandits with unknown reward probabilities, <img src="https://render.githubusercontent.com/render/math?math=\{ P_{1}, P_{2}, P_{3},.....,P_{K}\}">. </li>
    <li> At each time step <img src="https://render.githubusercontent.com/render/math?math=t">, we take an action <img src="https://render.githubusercontent.com/render/math?math=a_{t}\epsilon \textit{A}"> on one of the slot machine and receive a reward <img src="https://render.githubusercontent.com/render/math?math=r_{t}(a_{t})"> for the selected action (only). </li>
    <li> Objective : Maximize Cumulative Reward : <img src="https://render.githubusercontent.com/render/math?math=\sum_{t}{r_{t}}"> </li>
    <li> Another way to express this objective is through regret minimization, <img src="https://render.githubusercontent.com/render/math?math=R(t)=\sum_{t}{r_{t}(a^{*})-r_{t}(a_{t})}">, for not chossing the optimal action <img src="https://render.githubusercontent.com/render/math?math=a^{*}">.

<!---
# This is the title

Here's the table of contents:

1. TOC
{:toc}

## Basic setup

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-filename.md`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `filename` is whatever file name you choose, to remind yourself what this post is about. `.md` is the file extension for markdown files.

The first line of the file should start with a single hash character, then a space, then your title. This is how you create a "*level 1 heading*" in markdown. Then you can create level 2, 3, etc headings as you wish but repeating the hash character, such as you see in the line `## File names` above.

## Basic formatting

You can use *italics*, **bold**, `code font text`, and create [links](https://www.markdownguide.org/cheat-sheet/). Here's a footnote [^1]. Here's a horizontal rule:

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![](/images/logo.png "fast.ai's logo")

## Code

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |

## Footnotes

[^1]: This is the footnote.

-->
