---
description: >-
  With interfaces, you can execute prompts with series of questions using
  buttons, select menus, modals and more in a single ephemeral command to gather
  as much information you wish from the user.
icon: terminal
---

# Interfaces

#### How does it work?

The user runs the command `/anyCommand` and the prompt will begin as an ephemeral (only visible to you) reply with the first embed content and components based on your interface survey/application questions. when the user makes their choice they will have the option to either go to the next question or go back to the previous with 2 buttons, or they can just simply cancel the prompt. but above those buttons there will be any component you choose in each question and those will change based on what question the user is on.

#### How do i use it?

```
// Some code with comments explaining
```

#### <mark style="color:purple;">The prompt questions available are the following.</mark>

| JS Class (new)     | Data arguments             | Description                                         |
| ------------------ | -------------------------- | --------------------------------------------------- |
| StringSelectMenu() | placeholder, options       | Give the user options to choose from                |
| Modal()            | title, rows                | Prompt the user with a list of text based questions |
| BiButtons()        | each button with its value | Gives the user two options to choose from           |

