# Github Docs Example

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, and share** code.[<sup>[1]</sup>](#external-references)
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.
- In order to create Codeblocks in markdown you need to use three backticks(`)
-  Not to be confused with quotation(')

```
# Define a Person class
class Person
  # Constructor
  def initialize(name, age)
    @name = name # Instance variable for the person's name
    @age = age  # Instance variable for the person's age
 ```

Make a note of where the backtick button is located.
It should appear above the tab key but may vary based on the keyboard layout.

<img width = "200px" src = "https://github.com/dadadei/github-docs-example/assets/49823349/5bcc6a81-40a6-48a8-aaf3-c7cabd4b7303"/>

Good Cloud Engineers use Codeblocks for both code and errors that appear in the console.

```bash
Traceback(most recent call last):
```
> Here is an example of using a Codeblock for an error that appears in bash.

## Step 3 Use Github Flavoured Markdown Task List
Github extends Markdown to have a list where you can check off items.<sup>[2]</sup>

- [x] Finish Step 1
- [x] Finish Step 2

## Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes. 
Here are some examples:

|Name|Shortcode|Emoji|
| --- | --- | --- |
| Cloud |  `:cloud:` | :cloud: |
| Cloud with lighting |  `cloud_with_lighting` | 🌩️ |

## Step 5 - Create A Table

```md
|Name|Shortcode|Emoji|
| --- | --- | --- |
| Cloud |  `:cloud:` | :cloud: |
| Cloud with lighting |  `cloud_with_lighting` | 🌩️ |
```

![photo](assets/1.jpg)

[Secret Window](secret-window/hidden-garden.md)

## References
- http://github.com
- [official website github](http://github.com)<sup>[1]<sup>
- [Emoji](http://github.com)<sup>[2]</sup>
