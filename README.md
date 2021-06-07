# Using shortcuts to alternate parts of your text between uppercase and lowercase

We'll see shortcuts that could probably help you with text in ABAP: *CTRL+K*, *CTRL+L*, *CTRL+U*, *CTRL+J* and *CTRL+T* 

See the sample text below

```ABAP
write: / 'Lorem Ipsum Dolor Sit Amet,'.
write: / 'consectetur adipiscing elit.'.
```

CTRL+K alternates all the selected text between uppercase and lowercase

```ABAP
write: / 'lOREM iPSUM dOLOR sIT aMET,'. 
write: / 'CONSECTETUR ADIPISCING ELIT.'.
```

CTRL+L sets the selected text to lowercase.

```ABAP
write: / 'lorem ipsum dolor sit amet,'. 
write: / 'consectetur adipiscing elit.'.
```

CTRL+U changes the text to uppercase

```ABAP
write: / 'LOREM IPSUM DOLOR SIT AMET,'. 
write: / 'CONSECTETUR ADIPISCING ELIT.'.
```

CTRL+J sets all the first letters to uppercase.

```ABAP
write: / 'Lorem Ipsum Dolor Sit Amet,'. 
write: / 'Consectetur Adipiscing Elit.'.
```

CTRL+T sets only the first selected letter to uppercase.

```ABAP
write: / 'Lorem ipsum dolor sit amet,'. 
write: / 'Consectetur adipiscing elit.'.
```
