<head>
    <script src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML" type="text/javascript"></script>
    <script type="text/x-mathjax-config">
        MathJax.Hub.Config({
            tex2jax: {
            skipTags: ['script', 'noscript', 'style', 'textarea', 'pre'],
            inlineMath: [['$','$']]
            }
        });
    </script>
</head>

---
layout: default
---


# Description

## Example 1
![topo_example1](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example1.jpg)

The example 1 is a 16-resonator multiplexer with symmet-rical Chebyshev responses, which was described in [1]. The normalized specifications are 

* _Channel 1_: Passband: (−1.0, −0.75); Return loss level: 20dB;
* _Channel 2_: Passband: (−0.417, −0.167); Return loss lev-el: 20dB;
* _Channel 3_: Passband: (0.167, 0.417); Return loss level: 20dB;
* _Channel 4_: Passband: (0.75, 1.0); Return loss level: 20dB;
* Isolation levels within passband are better than 30dB.

The channel filter coupled with P2 occupies the Channel 4 and the channel filter coupled with P3 occupies the Channel 3. The channel filters connected with P4 and P5 are symmetric to that of P3 and P2, respectively. The external quality factors are calculated in advance, which are qe1 = 1.8628, qe2 = qe3 = qe4 = qe5 = 7.4512.

Based on the normalized specification, the objective function is defined as

$ e = m c^2 $ 

![](http://latex.codecogs.com/gif.latex?\\frac{\\partial J}{\\partial \\theta_k^{(j)}}=\\sum_{i:r(i,j)=1}{\\big((\\theta^{(j)})^Tx^{(i)}-y^{(i,j)}\\big)x_k^{(i)}}+\\lambda \\xtheta_k^{(j)})


![](http://latex.codecogs.com/gif.latex?\\frac{max((PB_1-(-20),0)}{20}+\frac{max((PB_2-(-20),0)}{20})

![](http://latex.codecogs.com/gif.latex?\\frac{1}{1+sin(x)})









### Specificatiion



## Example 2


![topo_example2](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/example2.jpg)



[1] X. Shang, Y. Wang, W. Xia, and M. J. Lancaster, "Novel Multiplexer Topologies Based on All-Resonator Structures," IEEE Transactions on Microwave Theory and Techniques, vol. 61, no. 11, pp. 3838-3845, 2013.

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

![Octocat](https://assets-cdn.github.com/images/icons/emoji/octocat.png)


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
