[![License](https://img.shields.io/badge/License-MIT-green.svg?style=plastic)](https://www.jg.codes/doc/licenses/mit/LICENSE) 
![Version](https://img.shields.io/badge/Version-Demo_1.0.01-blue.svg?style=plastic) 

# JG.Codes Responsive Design
## Quick Links
- [JG.Codes's Website](https://www.jg.codes/)  
- [Founder's Website](https://www.jonathan-gagne.com/)  

## What is JG.Codes Responsive Design?
JG.Codes Responsive Design is a very lite cross-browsers and cross-devices CSS framework's making website layout and design more flexible and easier than ever to be manipulate.  

The main goal of JG.Codes Responsive Design is to create a framework that could be learned into a maximum of fifteen minutes documentation reading.  

## Setup
Include that line of code into your head tag for a better performance  
~~~html
<link rel="stylesheet" href="//cdn.jg.codes/v1/jgc-responsive-design.min.css" />
~~~

We suggest to add these meta tags in your head tag to optimize the design responsiveness.
~~~html
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1.0, user-scalable=no" />
<meta name="apple-mobile-web-app-capable" content="yes" />
<meta name="mobile-web-app-capable" content="yes" />
~~~

## Documentation?
### Default Size Supported
Label | Abbreviation | Size Range (px)
:--- | :---: | ---:
Extra-Large | xl | > 1920
Large | lg | 1280 <> 1920
Medium | md | 960 <> 1280
Small | sm | 600 <> 960
Extra-Small | xm | < 600

### Size Unity
The size unity of a layout are based on a number divided by 12.  

Example:
- 1 is the 1/12 (~8%) of the total width
- 3 is the 3/12 (25%) of the total width
- 6 is the 6/12 (50%) of the total width
- 12 is the 12/12 (100%) of the total width

### Class Naming Convention
A class name for a cell always start by the prefix "jgc-rd-"  

Example
- `jgc-rd-1`
- `jgc-rd-3`
- `jgc-rd-6`
- `jgc-rd-12`

### Specific Size
It is possible to provide extra option based on the size of the screen.  

Example
- `jgc-rd-12-md4` - Size of 12/12 by default, and 4/12 when it is medium
- `jgc-rd-2-lg6-md3` - Size of 2/12 by default, 6/12 when it is large, and 4/12 when it is medium

### Size Smaller Than
You can apply a style a range of size smaller than a specific size.

Example
- `jgc-rd-6-smd12` - Size of 6/12 by default, and 12/12 when it is smaller than medium
- `jgc-rd-3-slg6` - Size of 3/12 by default, and 6/12 when it is smaller than large

### Hide and Show Feature
You can hide and show a cell with the feature "hide" and "show". Moreover, they work as well with "Specific Size" and the option "Size Smaller Than"

Example
- `jgc-rd-hide` - Hide the cell
- `jgc-rd-xshide` - Hide the cell when it is extra-small
- `jgc-rd-hide-smdshow` - Hide the cell by default, and show the cell when it is smaller than medium
- `jgc-rd-6-mdhide` - Size of 6/12 by default, hide the cell when it is medium

## Example
To see example files click [here](/example/).  
To see a basic example click [here](https://www.jg.codes/JGC-Responsice-Design/basic.html).  
To see a layout example click [here](https://www.jg.codes/JGC-Responsice-Design/layout.html).  

## Authors
* Jonathan Gagne - *Founder* - [Jonathan Gagne's Website](https://www.jonathan-gagne.com/).  
* JG.Codes - *Community* - [JG.Codes's Website](https://www.jg.codes/).  

## License
This project is licensed under the MIT License.  
See the [LICENSE](https://www.jg.codes/doc/licenses/mit/LICENSE) for details.  

## Code of Conduct
We, as the community behind this project, are committed to making participation in this project a harassment-free experience for everyone, regardless of the level of expertise, gender, gender identity and expression, sexual orientation, disability, personal appearance, body size, race, ethnicity, age, religion or nationality.  

See the [CODE OF CONDUCT](https://www.jg.codes/doc/CODE_OF_CONDUCT) for more details.