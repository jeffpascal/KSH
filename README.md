- [KSH](#ksh)
  - [First line](#first-line)
  - [Understand variables](#understand-variables)

# KSH
Learning KSH


## First line

```sh
#!/bin/ksh
# the above must always be the first line. But generally, lines
# starting with '#' are comments. They dont do anything.
# This is the only time I will put in the '#!/bin/ksh' bit. But
# EVERY EXAMPLE NEEDS IT, unless you want to run the examples with
#  'ksh filename' every time.
#
# If for some odd reason, you dont have ksh in /bin/ksh, change
# the path above, as appropriate.
#
# Then do  'chmod 0755 name-of-this-file'. After that,
# you will be able to use the filename directly like a command

echo Yeup, you got the script to work!
```

## Understand variables

In shellscripts, a variable can contain a collection of letters and/or numbers [aka a 'string'] , as well as pure numbers.

You set a variable by using

```variablename="some string here"```

  OR

```variablename=1234```

You access what is IN a variable, by putting a dollar-sign in front of it.

```echo $variablename```

  OR

```echo ${variablename}```

If you have JUST a number in a variable, you can do math operations on it.

