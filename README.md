# Regex-Email-Tutorial

## Description

```md
AS A web development student
I WANT a tutorial explaining a specific regex
SO THAT I can understand the search pattern the regex defines
```

## The Email Regex

```md
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/
```

I chose to use the email regex. I have used this regex in the past and I basically copied and pasted the code without knowing how the code actually completes the task. I picked the email regex to better understand my past code and to improve my future code. The regex is split up into 4 sections listed below.

## Table of Contents

- [One Line](#one-line)
- [Before The At](#before-the-at)
- [After The At](#after-the-at)
- [Dot Com](#dot-com)
- [Contact Info](#contact-info)

## One line

The ^ sign indicates that we should be looking at the beginning of the line and the $ sign inidicates that we should also be looking at the end of the line. When these two signs are together, it means that we are going to be looking for something that is contained by itself on the same line.

## Before The At

```md
([a-z0-9_\.-]+)
```

"Before The At" is reffering to the @ sign. In this case, it is being used literally to search for an @ sign. It was easier to break up the regex by using the @ sign for reference. That is why I included a before and after the at ( @ ).

The regex code above is saying that we can use and letter from a to z, any number from 0 to 9, and the special characters; underscore ( _ ), period ( . ), or a dash ( - ). The forward slash followed by a period means that we are looking for a literal period ( . ) instead of it's other meaning of including all characters. The plus sign ( + ) means that we have to have at least one character in this field, therefore it cannot be left blank. This is all located before the @ sign in an email. 

## After The At

```md
([\da-z\.-]+)
```

The \d means that we will be looking again for any number between 0 and 9. The characters after the  at ( @ ) sign can also include any letter from a to z. The forward slash followed by a period means that we are looking for a literal period ( . ) instead of it's other meaning of including all characters. That means that the characters after the @ can include a period ( . ) or dash ( - ) as well. The plus sign ( + ) means that we have to have at least one character in this field, therefore it cannot be left blank.

## Dot Com

```md
\.([a-z\.]{2,6})
```

The title is a little misleading. We are looking for a " .com " but this code will also look for " .net " , ".edu ", etc. Once again, the forward slash followed by a period means that we are looking for a literal period ( . ). This time it is being used before the parenthesis. That means that it needs to be there instead of being an option like before. After the dot, the characters can contain any letter from a to z and even another dot. The {2,6} means that the characters have to be between 2 and 6 in length. 

## Contact Info

GitHub username: Priddle88

GitHub profile: [Link to Profile](https://github.com/Priddle88)

Reach out to parkerriddle09@gmail.com (with your first name included) if you have any questions!
