## What is Lyntax?

It stands for Laravel Syntax.

**What Does It Do:**

It is similar to the work of blade in Laravel. But Lyntax can be used in Laravel's backend codes. It shortens the codes and increases the readability of the codes in Laravel.

**Pay Attention To The Examples:**

Without Lyntax:

```
$a=20;

$b=30;

echo $a.$b;

function test($var){
  return $var;
}
```

With Lyntax:

```
$a=20;
$b=30;

*=$a.$b;

func-> test($var){
*|$var;
}
```
