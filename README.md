*This proyect has been created as part of the 42 curriculum by emarin-m.*
# GET_NEXT_LINE

## :next_track_button: Want to get a text line-by-line?

### :open_book: Introduction
If all you've dreamt about in your life is having a program to get you *El Quijote* line-by-line, this is your 42 project. That's it, that's what it does, there's no more introduction to be done.

<blockquote style="border-left: 4px solid #f85149; background-color: rgba(0.05); padding: 10px;">
<p style="margin-left: 10px;"> ⚠️ <strong>DISCLAIMER</strong>
<br>
<i>If you're a 42 student: 42 projects must be CODED by yourself. Do not copy this project into yours. You will learn nothing by doing that. Exams are completed without Internet connection; you're alone with your IDE. The porpuse of these repositories is to show what we do at 42 and, yes, if you're stucked at some point, learn something new, but give peer-to-peer a chance first</i> 😉.</p>
</blockquote>


### :dart: Example
We'll get back to how to execute the code, but for now, here's an example of how the terminal output should look like:

<img width="100%" height="100%" alt="A screenshot from the terminal output after executing get_next_line program" src="https://i.imgur.com/9HpFpUy.png" />

### :paperclip: User instructions

1. Clone this repository on your computer:
```bash
git clone git@github.com:evamarinma/get_next_line.git
```
<br>

2. Modify `input.txt` file with the text you want.
<br>
3. Compile the code. You can do it in different ways, depending on the file descriptor you want to use.
* If you just want your `input.txt` file to be used as `fd` use this command:
```bash
cc *.c -o get_next_line && ./get_next_line | cat -e
```

* Let's say you didn't want to read through the whole `input.txt` file. You're only interested in getting the lines containing character 'e'. You can do so like this:
```bash
cc *.c -o get_next_line && grep e input.txt | ./get_next_line | cat -e
```

<blockquote style="border-left: 4px solid  #8ADFD7; background-color: rgba(0.05); padding: 3px;">
<p style=" margin-left: 10px;">Here's an example of how this output should look like:</p>
</blockquote>

<img width="100%" height="100%" alt="stdin 0 get_next_line example" src="https://i.imgur.com/NhZQTtr.png" />
<small>*Get creative and try different ways to get lines from an input through the terminal!*</small>




