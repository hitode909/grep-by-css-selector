# grep-by-css-selector

Print URLs which has the specified element.

```
echo <URL> | bundle exec -- ./grep-by-css-selector <CSS_SELECTOR>
```

## Example

```
% echo "http://blog.sushi.money/\nhttp://blog.sushi.money/about" | bundle exec -- ./grep-by-css-selector ".social-button-item"
http://blog.sushi.money/
```
