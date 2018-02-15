---
title: Interactive work to test and undestand algorithms
description: In this section, we describe a workflow combining interactive work and consolidation.

---
## First Try

```yaml
type: MultipleChoiceExercise
key: 288a54c5fc
lang: python
xp: 50
skills: 2
```
Try

- print('Hello, World!')
- print("Hello, World!")
- print?
- print('?"')

Which one generates the help messages?
`@instructions`
- print('Hello, World!')
- print("Hello, World!")
- print?
- print('?"')
 
`@hint`

`@pre_exercise_code`
```{python}

```

`@sct`
```{python}

msg1 = "Incorrect."
msg2 = "Incorrect."
msg3 = "Correct!"
msg4 = "Incorrect."
test_mc(3, [msg1, msg2, msg3, msg4])
```
