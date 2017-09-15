## pandoc-beamer

Generate pdf slideshow using pandoc and beamer.


```
docker run -it --rm -u $UID:$GID -v $PWD:/work -w /work test.md -V theme:Singapore -V colortheme:seahorse -o test.pdf
```

with test.md:

~~~
% Habits
% John Doe
% March 22, 2005

# In the morning

## Getting up

- Turn off alarm
- Get out of bed

## Breakfast

- Eat eggs
- Drink coffee

# In the evening

## Dinner

- Eat spaghetti
- Drink wine

------------------



## Going to sleep

- Get in bed
- Count sheep
~~~

[Beamer theme matrix](https://hartwork.org/beamer-theme-matrix/)
