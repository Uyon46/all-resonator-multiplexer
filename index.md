---
layout: default
---


# Examples list



## [Example1](./Example1.md)  
![topo_example1](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example1.jpg)

The example 1 is a 16-resonator multiplexer with symmet-rical Chebyshev responses, which was described in [1]. The normalized specifications are 

* _Channel 1_: Passband: (−1.0, −0.75); Return loss level: 20dB;
* _Channel 2_: Passband: (−0.417, −0.167); Return loss lev-el: 20dB;
* _Channel 3_: Passband: (0.167, 0.417); Return loss level: 20dB;
* _Channel 4_: Passband: (0.75, 1.0); Return loss level: 20dB;
* Isolation levels within passband are better than 30dB.

The channel filter coupled with P2 occupies the Channel 4 and the channel filter coupled with P3 occupies the Channel 3. The channel filters connected with P4 and P5 are symmetric to that of P3 and P2, respectively. The external quality factors are calculated in advance, which are qe1 = 1.8628, qe2 = qe3 = qe4 = qe5 = 7.4512.

Based on the normalized specification, the objective function is defined as

![obj1](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/costfunc1_f.png)



## [Example2](./Example2.md)  

![topo_example2](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/example2.jpg)

Example 2 is a 10-resonator diplexer with asymmetric channel responses. The topology was introduced in [2]. The normalized specifications are

* _Channel 1_: Passband: (−1, −0.661); Return loss level: 20dB.
* _Channel 2_: Passband: (0.709, 1.0); Return loss level: 20dB. 
* Isolation levels within passbands are better than 80dB.

The branch coupled with P2 occupies the Channel 1 while the one coupled with P3 occupies the Channel 2. 
The external quality factors are qe1 = 3.0818, qe2 = 5.7326 and qe3 = 6.6648. 

Based on the normalized specification, the objective function is defined as

***




## [Example3](./Example3.md)  

![topo_example3](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example3.jpg)

Example 3 is a 9-resoantor diplexer with cross-couplings in two channels which make the optimization more difficult than the first two examples. This topology was proposed in [3]. The normalized specifications are 

* _Channel 1_: Passband: (−1, −0.203); Return loss level is better than 20dB;
* _Channel 2_: Passband: (−0.026, 1); Return loss level: 20dB;
* Isolation levels within passbands are better than 30dB.

The channel filter coupled with P2 occupies the Channel 1 while the other channel filter occupies the Channel 2. The external quality factors are qe1 = 1.0475, qe2 = 2.3395 and qe3 = 1.8969. Based on the normalized specifications, the objective function is defined as 




## [Example4](./Example4.md)  

![topo_example4](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example4.jpg)

Example 4 is a 12-order diplexer. Existing the shared resonator 4, the topology of example 4 contains 4 cross-couplings. and the specifications demand high isolations within the passband and narrow guard band. The main ideas of this topology were referred to [4].

The normalized specifications of example 4 are 
* _Channel 1_: Passband: (−1, −0.1); Return loss level: 20dB; 
* _Channel 2_: Passband: (0.2, 1.0); Return loss level: 20dB;
* Isolation levels within the passbands are better than 60dB.

In the topology, the branch coupled with port P2 occupies the Channel 1 while another branch occupied the Channel 2. The external quality factors are obtained in advance, which are qe1 = 1.1733, qe2 = 2.2145 and qe3 = 2.4955. 


***


## [Example5](./Example5.md)  

![topo_example5](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example5.jpg)

Example 5 is a 18-resonator triplexer. The normalized specifications are
* _Channel 1_: Passband: (−1, −0.6); Return loss level is better than 20 dB;
* _Channel 2_: Passband: (−0.25, 0.25); Return loss level is better than 20 dB; 
* _Channel 3_: Passband: (0.4,1); Return loss level is better than 20 dB;
* Isolation levels within passbands are better than 30dB.

The number of variables is 35. The branch connected with P2 occupies the Channel 1, the branch connected with P3 occupies the Channel 2. The rest one occupies the Channel 3. The external quality factors are qe1 = 1.3253, qe2 = 4.9700, qe3 = 3.9760 and qe4 =3.3133. According to the normalized specification, the objective function is defined as

$ a+b=1 $



## [Example6](./Example6.md)   
![topo_example6](https://github.com/Uyon46/all-resonator-multiplexer/raw/master/topo_example6.jpg)

Example 6 is a triplexer which is shown in Fig. 11. The specifications are

* _Channel 1_: Passband: (−1, −0.578); Return loss level is better than 20 dB;
* _Channel 2_: Passband: (−0.485, −0.051); Return loss lev-el is better than 20 dB; 
* _Channel 3_: Passband: (0.684,1); Return loss level is bet-ter than 20 dB;
* Isolation levels within passbands are better than 30dB.

The number of variables is 27. The branch connected with P2 occupies the Channel 1, the branch connected with P3 occpies the Channel 2 and the rest one occupies the Channel 3. The external quality factors are qe1 = 1.5191, qe2 = 4.8496, qe3 = 3.8068 and qe4 = 5.2794. The variables and group division are listed in Table XII. The variables with hint values are listed in the Table XVIII




[1] X. Shang, Y. Wang, W. Xia, and M. J. Lancaster, "Novel Multiplexer Topologies Based on All-Resonator Structures," IEEE Transactions on Microwave Theory and Techniques, vol. 61, no. 11, pp. 3838-3845, 2013.  
[2]	B. Liu, H. Yang, and M. J. Lancaster, “Global optimization of micro-wave filters based on a surrogate model-assisted evolutionary algorithm,” IEEE Trans. Microw. Theory Techn., vol. 65, no. 6, pp. 1976–1985, Jun. 2017.  
[3] Y. Wu, Y. Wang and E. A. Ogbodo, "Microstrip wideband diplexer with narrow guard band based on all-resonator structures," in 2016 46th Eu-ropean Microwave Conference (EuMC), London, United Kingdom, 2016, pp. 1163-1166.  
[4] Y. Wu, R. Wu and Y. Wang, “A Compact Coupling Structure for Di-plexers and Filtering Power Dividers,” Progress In Electromagnetics Re-search, vol. 69, pp. 161-170, 2018.  



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
