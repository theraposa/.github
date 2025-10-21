# theraposa

A fast, lightweight and beautiful scripting language.
| name | pronounciation | type |
| :------- | :------: | -------: |
| Theraposa   | therəˈfōsə   | scripting   |

## Getting Started
To see a full guide on the [syntax](https://en.wikipedia.org/wiki/Syntax) of Theraposa, please see [GRAMMAR.md](GRAMMAR.md). This guide will just go over the simple basics of Theraposa. Like I said above, it is a [scripting language](https://en.wikipedia.org/wiki/Scripting_language), so it doesn't have as many capabilities to other languages. If you wish to have many features in a language I do not reccomend Theraposa. Theraposa has a standard library that is quite small, with things such as [io], [fs], and [pth]. Allowing you to manipulate and read things such as [input and output](https://en.wikipedia.org/wiki/Input/output) of the [command line](https://en.wikipedia.org/wiki/Command-line_interface), [file](https://en.wikipedia.org/wiki/File) system management for creating and opening and writing to [files](https://en.wikipedia.org/wiki/File), and the pth which stands for [path](https://en.wikipedia.org/wiki/Path_(computing)), allowing for path manipulation. 

Now, lets get into how you can get started with Theraposa and its syntax.

#### Primitives
```ther
"Hello, world!" ~~ Double-string
'Hello, world!' ~~ Single-string
10              ~~ Number
                ~~ Anything else will result in a error unless used in variables.
true            ~~ Boolean option one
false           ~~ Boolean option two
yes             ~~ Boolean option one
no              ~~ Boolean option two
```

#### Variables
```ther
stash ~~ Mutable variables
vault ~~ Immutable variables
```

#### Operators
```ther
+ ~~ Addition
- ~~ Subtraction
* ~~ Multiplication
/ ~~ Division
% ~~ Modulus
```

#### Conditionals
```ther
if random_thing {
return true ~~ Returns true
} else {
return false ~~ Returns false
}
```

#### Modules
```ther
get module name
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) to learn about how you can contribute. Thank you so much for being interested in my little project!
