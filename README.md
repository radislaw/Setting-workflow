# Setting-workflow
## Использование Sass
* gem install sass
* sass --watch .
* Nesting:
```CSS
p{
  a{
    color:red;
    }
}
```
* Advance nesting: 
```CSS
  p{
    a{
      color:red;
      &:hover{
        opacity:0.5;
        }
      }
    }
```
