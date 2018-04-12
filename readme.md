
# The ~~Medium~~ Computers is the Message

Computer science has evolved to solve problems at scale through collaborating on software using the internet.


```python
    %reload_ext pidgin
    %pidgin markdown test conventions
```


```python
    class Test(__import__('unittest').TestCase):
        def testLitAF(Test):
            import litaf
            assert litaf.LiterateProgramming
        def testImports(Test):
            import references
            from utils import style
            assert references, style
```


    class Test(__import__('unittest').TestCase):
        def testLitAF(Test):
            import litaf
            assert litaf.LiterateProgramming
        def testImports(Test):
            import references
            from utils import style
            assert references, style


    The pidgin extension is already loaded. To reload it, use:
      %reload_ext pidgin
    <sweet.test.Result run=2 errors=1 failures=0>
    
    {<__main__.Test testMethod=testImports>: 'Traceback (most recent call last):\n  File "<ipython-input-4-bfa3932139bd>", line 7, in testImports\n    from utils import style\nModuleNotFoundError: No module named \'utils\'\n'}



```python
    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
    %pidgin --off markdown
```


    if __name__ == '__main__':
        !jupyter nbconvert --to markdown readme.ipynb
    %pidgin --off markdown

