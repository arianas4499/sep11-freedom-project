# Entry 5
##### 04/20/23

### Introduction
As we continue to work on our tool we're also including our tool into our own projects. In the previous blog entry I talked about my process with making my map. In this blog I will explain my process with making my character.

### Process
My first step was to make my chatacter able to move. In order to do this I had to use .setMaxVelocity and .setFriction. .setMaxVelocity would be the speed the character would be walking and jumping at.

'
this.body.setMaxVelocity(3,2);
this.body.setFriction(0.4,0);

'
Its pretty slow but that will be changed later on.

The next thing I did was making the chatacter be able to move by setting certain keys on the keyboard to certain values. This part was pretty long but I basically did :
'
me.input.bindKey(me.input.KEY.LEFT,"left");
'

This continued on for another 7 lines of code. The rest were the same except for the fact that the key is different and it does something different.

### EDP
I am currently on the Design process of the engineering design process. I will be on tbis for a while because we are still working on our JS Game until the day of the expo. A skill I am learning is googling because when there is a line of code that I do mot understand I can google for an explanation.

[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)