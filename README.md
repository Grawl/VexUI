# VexUI

A [VexFlow](http://www.vexflow.com/) Editor for creating **and playing** music.

## Using

```html
<div id="container"></div>
<script type="text/javascript">
    var handler = new Vex.UI.Handler("container").init();
</script>
```

## [Working demo](http://andrebakker.github.io/VexUI/) 

- Add new notes
- Select note length
- Add rest
- Make notes a chord
- Add note / chord options:
  - Add double flat to key
  - Add flat to key
  - Add natural to key
  - Add sharp to key
  - Add double sharp to key
  - Add dot to key
  - Beam with next note
  - Tie with next note
- Remove note / chord (key)
- Add new note between other notes
- Add bars
- Add clefs
- Change duration of note to add by mouse wheel
- **Listen your music!**

## Motivation

Mohit Muthanna created an awesome music rendering JavaScript library called [VexFlow](http://www.vexflow.com/). The only problem is that there is no "WYSIWYG" editor. This project tries to achieve just that!

## Contributors

Please, please! You are more than welcome to contribute. It's been such a long time since I've been able to work on this project. Maybe you can help it get better?

There is so much to do. For example:

- Toolbar needs buttons for bars and clefs. For now, the only way to change to clefs and bars is by using mouse middle button;
- Toolbar needs an area to set key and time signatures, and RPM;
- Implement ties;
- Implement mute notes;
- Add support for text;
- Much, much more!

## MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

## Links

* [VexFlow Home](http://vexflow.com)
* [My VexFlow](http://my.vexflow.com)
* [Mohit Muthanna](http://0xfe.muthanna.com)