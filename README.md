# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code.
A good __Cloud Engineer__ uses Codeblocks whenever possible.

Because it allows others to copy and past their code to replicate or research issues.


- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with quotation (')

```
# Create an empty array to store names
names = []

# Get names from the user until they enter an empty string
loop do
  print "Enter a name (or press Enter to finish): "
  name = gets.chomp
  break if name.empty?
  names << name
end

# Sort the names alphabetically
sorted_names = names.sort

# Display the sorted names
puts "Sorted Names:"
sorted_names.each do |name|
  puts name
end
```

- When you can you should attempt to apply syntax highlighting to your codeblocks.

```ruby
# Create an empty array to store names
names = []

# Get names from the user until they enter an empty string
loop do
  print "Enter a name (or press Enter to finish): "
  name = gets.chomp
  break if name.empty?
  names << name
end

# Sort the names alphabetically
sorted_names = names.sort

# Display the sorted names
puts "Sorted Names:"
sorted_names.each do |name|
  puts name
end
```

- Make note of where the backtick button is located.
- It should appear above the tab key,
- but it may vary based on your keyboard layout.
<img width="403px" alt="backtick" src="https://github.com/awkamara/Github-docs-example-1/assets/145500282/a7cdc3b0-facf-4618-bde7-fef800abcb59">

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console
```bash
Traceback (most recent call last):
  sample.rb:3:in `<main>'
sample.rb:3:in `[]': index 1 outside of array bounds (IndexError)
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavoured Markdown Task Lists

Github extends Markdown to hava a list where you can check off items. [<sup>[1]</sup>](#external-references)


- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

Github Flavoured Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | ShortCode | Emoji |
| --- | --- | --- |
| cloud | :cloud: | :cloud: |
| cloud with lighting | `:cloud_with_lighting` | 🌩️ |

# Step 5 - how to create a table


You can use the following markdown format to create tables:

```md
| Name | ShortCode | Emoji |
| --- | --- | --- |
| cloud | :cloud: | :cloud: |
| cloud with lighting | `:cloud_with_lighting` | 🌩️ |
```
 Github extends the functionality of Markdown tables to provide more alignment and table cell formatting options. [<sup>[2]</sup>](#external-references)

![Photo of the pipe character on our keyboard](assets/pipe-char.jpeg)
 
## External References

- [GitHub Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Basic writing and formatting syntax (Github flavoured Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Task List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>
