# Comment
**Code**  
```
<!--Comment-->
```
**Result**  
<!--Comment-->
[Note: This code is used for commenting in Markdown.No output will show ]

# Heading Tags
**Code**   

```
# h1
## h2
### h3
#### h4
##### h5
###### h6
```
**Result** 
# h1
## h2
### h3
#### h4
##### h5
###### h6

# Italic

**Code**  
```
_italic_
```
**Result**  
_italic_

# Bold  

**Code**  
```
**Bold**
```
**Result**  
**Bold**

# Strick Through
**Code**  
```
~~Strick Through~~
```
**Result**  
~~Strick Through~~

# Horizontal Line
**Code**  
```
---
or
___
```
**Result**

---
___

# Block Quotes
**Code**  
```
>This is a Block Quotes
```
**Result**
>This is a Block Quotes

# Links
**Code**  
```
[Google](https://www.google.com/)
```
**Result**  
[Google](https://www.google.com/)

# Lists
## Unordered lists
**Code**  
```
* i1  
* i2 
    * i3
```
**Result**  
* i1  
* i2 
    * i3

## Ordered list
**Code**  
```
1. i1  
2. i2 
3. i3
```
**Result**  
1. i1
2. i2
3. i3

# Inline Code Block

**Code**  
```
`<p># h1</p>`
```
**Result**  
`<p># h1</p>`

# Image

**Code**  
```
![Owl](owl.png)
```
**Result**  
![Owl](owl.png)

# Code Block

**Code**  
```
    [Note: any code between 
    ```
        
    ```
    ]
```
**Result** 
```python
print("Hello fellow knight owl")
```

# Task list 
**Code**
```
*[] not checked
*[x] checked
```
**Result**

* [ ] not checked
* [x] checked 

[Note: Previews in github website]

# Tables
**Code**

```
| Col 1 | Col 2 | Col 3 |
| :---: | :--- | ---: |
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |

[Note: :---: means center aligned]
[Note: ---: means right aligned]
[Note: :--- means left aligned]
```
**Result**

| Col 1 | Col 2 | Col 3 |
| :---: | :--- | ---: |
| Row 1, Col 1 | Row 1, Col 2 | Row 1, Col 3 |
| Row 2, Col 1 | Row 2, Col 2 | Row 2, Col 3 |
| Row 3, Col 1 | Row 3, Col 2 | Row 3, Col 3 |

extra:
row or col marge is not possible in Markdown language but it support the use of **html and asci code** so we can make those kind of table using this language in .md file
For example:  

**Code**
```
<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>Layer 1</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>
```
**Result**  

<table>
    <thead>
        <tr>
            <th>Layer 1</th>
            <th>Layer 2</th>
            <th>Layer 3</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan=4>Layer 1</td>
            <td rowspan=2>L2 Name A</td>
            <td>L3 Name A</td>
        </tr>
        <tr>
            <td>L3 Name B</td>
        </tr>
        <tr>
            <td rowspan=2>L2 Name B</td>
            <td>L3 Name C</td>
        </tr>
        <tr>
            <td>L3 Name D</td>
        </tr>
    </tbody>
</table>
# Diff
**Code**

```diff  
- This line is Deleted.
+ This line is Added.
```

# Nesting quotes

**Code**
```
    > One.
    >> One.
    >>> One.

    >>>> One.

    >>>>> One.
```

**Result**

> One.
>> One.
>>> One.

>>>> One.

>>>>> One.

#Collapsible content
**Code**
```
<details>
    <summary>Click to see more!</summary>
          
     ## More awesome tips!
    - item 1 
    - item 2
</details>
```

**Result**

<details>
    <summary>Click to see Owls!</summary>  
    
    Owl types
        - Black Owl  
        - Gray Owl
</details>

<!--This was made with the help of freeCodeCamp-->

<!--Cheatsheet link: https://github.com/zairahira/Markdown-cheatsheet -->
