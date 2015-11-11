# Basics
|Mapping               | Summary                                                                                  |
|----------------------|----------------------------------------------------------------------------------------- |
|`<esc>`               |Exit out of any mode back into normal mode                                                |
|:q or :quit           |Quit out of Vim                                                                           |
|:w or :write          |Write the current file                                                                    |
|j, k 	               |Move the cursor down / up                                                                 |
|h, l 	               |Move the cursor left / right                                                              |
|i 	                   |Go into "insert mode" to enter text                                                       |
|x 	                   |Delete the character under the cursor                                                     |


# Motions and moving
## Moving within a line

|Mapping               | Summary                                                                                  |
|----------------------|--------------------------------------------------------------------------------          |
|w                     |move forward one (**w**)ord                                                               |
|b                     |move (**b**)ackward one word                                                              |
|e                     |move forward to the (**e**)nd a word                                                      |

## Jumping within a line
|Mapping               | Summary                                                                                  |
|----------------------|------------------------------------------------------------------------------------------|
|f`<char>`             |(**f**)ind a character forward in a line and move to it                                   |  
|t`<char>`             |find a character forward in a line and move un(**t**)il it (one character before)         |
|F`<char>`             |(**f**)ind a character backward in a line and move to it                                  |
|T`<char>`             |find a character backward in a line and move un(t)il it                                   |
|;                     |repeat last f, t, F, or T command                                                         |
|,                     |repeat last f, t, F, or T command, but in opposite direction                              |

## Moving between lines
|Mapping               | Summary                                                                                  |
|----------------------|------------------------------------------------------------------------------------------|
|j, k                  |move up/down one lineard in a line and move to it                                         |
|H, M, L               |move (**H**)igh, (**M**)iddle, or (**L**)ow within the viewport                           |
|/                     |search                                                                                    |
|n                     |repeat last search                                                                        |
|N                     |repeat last search in opposite direction                                                  |
|C-u, C-d              |move (**u**)p or (**d**)own                                                               |
|`<NN>`G               |(**G**)o to line number NN (useful if you have a failing test on a given line)            |


# Command Language  
## Commands
|Mapping               | Summary                                                                                  |
|----------------------|------------------------------------------------------------------------------------------|
|d                     |**D**elete                                                                                |
|c                     |**C**hange                                                                                |
|y                     |**Y**ank(copy)                                                                            |
|v                     |**V**isually select                                                                       |
|`>`,`<`               |indent, dedent                                                                            |
|=                     |reformat (reindent, break long lines, etc)                                                |

## Using Motions
|Mapping               | Summary                                                                                  |
|----------------------|------------------------------------------------------------------------------------------|
|de                    |**D**elete to the end of the current word                                                 |
|d2e                   |**D**elete to the end of next word                                                        |
|dj                    |Delete down a line (current and one below)                                                |
|dt)                   |Delete up until next closing parenthesis                                                  |
|d/world               |Delete up until the first search match for "world"                                        |

## Commands
|Mapping               | Summary                                                                                  |
|----------------------|------------------------------------------------------------------------------------------|
|iw, aw                |"inner word", "a word" (a word includes the space)                                        |
|ip, ap                |"inner paragraph", "a paragraph" ("a" includes the newline)                               |
|i),a)                 |"inner parenthesis", "a parenthesis" (includes the parens)                                |
|i', a'                |"inner single quote", "a single quote" (includes the quotes)                              |
|i", a"                |"inner double quote", "a double quote" (includes the quotes)                              |
|it, at                |"inner tag", "a tag" (includes the open and closing tag)                                  |
