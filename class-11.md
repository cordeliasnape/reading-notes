## When should you use an unordered list in your HTML document?

You could use an unordered list when you wish to create a list that doesn’t have an order or numbers proceeding it.

### How do you change the bullet style of unordered list items?

You can target the bullet point in CSS using `list-style-type`. For example:

> list-style-type: circle;
> list-style-type: square;

## When should you use an ordered list vs an unordered list in your HTML document?

You should use an ordered list when you wish to proceed it with a number, for example, if you wish to make a ‘top ten’ list.

### Describe two ways you can change the numbers on list items provided by an ordered list?

You can target the numbers in an ordered list by using the same `list-style-type` as before. For example:

> list-style-type: upper-roman;
> list-style-type: lower-alpha;

## Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?

Once, there was a blue box. The box had ‘The Box Model’ scrawled over it in permanent marker. A green cat named Padding wandered over to the box. Padding wants to lay down along the inner parameter of the box, and when he grows, he can make the box bigger. An orange cat named Margin didn’t wish to sit inside the box, he lay down along the outside of the box, protecting the box from the objects around it. And it was all a dream.

## List and describe the four parts of an HTML elements box as referred to by the box model.

- The content - the content can be an image, paragraph, header or anything placed in your site.
- The padding - the padding fills out the space in between the content and border.
- The border - the border surrounds the padding and content in the form of a line.
- The margin - the margin gives space around the border.

## What data types can you store inside of an Array?

- numbers
- strings
- boolean values (true and false)
- characters
- objects

### Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?

> const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

It is a valid array but it doesn’t have equal values. If I wanted to access Pete’s age, I would say:

> const peteAge = people[0][1];

This is because I am accessing the first array (which has index 0), and accessing the second value in the array (which has index 1).

## List five shorthand operators for assignment in javascript and describe what they do.

1. `=` : assignment
2. `+=` : addition assignment (adds the first value to answer)
3. `-=` : subtraction assignment
4. `*=` : multiplication assignment
5. `/=` : division assignement

### Read the code below and evaluate the last expression and explain what the result would be and why.

> let a = 10;
> let b = 'dog’;
> let c = false;

> // evaluate this
> (a + c) + b;

10 + false = 10
10 + ‘dog’ = 10dog

### Describe a real world example of when a conditional statement should be used in a JavaScript program.

An ‘if’ statement is a conditional statement, and it can be used to say ‘if it’s this, then do that or else, if it’s not that, then do this instead’.

### Give an example of when a Loop is useful in JavaScript.

Loops can be useful to make a value appear as many times as the length of something.
