
# A Notebook is a Hypothesis

> Blending the paradigms of modern science and open source software



```python
    %reload_ext pidgin
    %pidgin markdown test conventions
```


```python
Testing and documentation are critical features in reusable open source software.  These best practices evolved from the need for community development of software for people to read and write.  Generations of open source software have established idioms and style guides to enable software development at a global scale.  Access to resuable software is blending with modern science which shares a similar global ambition to solve increasing complex, multi-objective engineering problems.

Modern scientists are transitioning to a generation where notebooks are common currency.  Notebooks are evolving past a medium for personal insight to assets for communities innovation.  Notebooks are becoming extrapersonal objects to scientists that evaluated procedural units of thought as computational ideas.  In a way, notebooks are a modern hypothesis and scientists must become comfortable with sharing them quicker.  

Unfortunately, many new notebook authors lack conventions for sharing notebooks with a community.  This talk 
will present tactics from literate programming to create readable, reusable, and reproducible notebooks.  These notebook authoring practices promote improved documentation and unit testing.
```


```python
    class Test(__import__('unittest').TestCase):
        def testLitAF(Test):
            import litaf
            assert litaf.LiterateProgramming
        def testImports(Test):
            import references
            from litaf.utils import style
            assert references, style
```


```python
    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
    %pidgin --off markdown
```
