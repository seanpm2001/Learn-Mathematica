
***

![/Mathematica_Logo.png](/Mathematica_Logo.png)

### Learning Mathematica

I am not too experienced with Mathematica at the moment. This document will go over my knowledge of the Mathematica language so far.

This document used various version 8.0.4 of the Wolfram Mathematica programming language.

#### Comments in Mathematica

Comments in Mathematica are unique, but still easy to do.

```mathematica
(* This is a single line comment *)
(* The syntax for a multi-line
comment uses the same syntax
as a single line comment *)
```

This example works with every version of Mathematica.

#### Break keyword in Mathematica

Mathematica does NOT support the `break` keyword.

To this day, I am still not entirely sure what the `break` keyword does, but most languages support it.

_/!\ This example has not been tested yet, and may not work_

#### Hello World in Mathematica

A hello world program in Mathematica is a bit more complicated than a Python or Perl Hello World program, but it isn't very difficult either. It is not similar to any language I am currently familiar with.

```mathematica
Print[ OutputForm["Hello World"] ];
(* Output:*)
(* Hello World *)
```

This example works with every version of Mathematica (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### Integers in Mathematica

I think this is how you implement integers in Mathematica

```mathematica
int x -> 2;
int y -> 32;
Print[ OutputForm[2^32] ];
```

This example works with every version of Mathematica (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### Booleans in Mathematica

Booleans are defined like so in Mathematica:

```mathematica
int x -> 4;
bool isEven -> True
bool isOdd -> False
Print[ OutputForm[x] ];
```

This example works with every version of Mathematica (as far as I know)

_/!\ This example has not been tested yet, and may not work_

#### Packages in Mathematica

Here is a Mathematica package I commonly use as an example. I don't entirely know what it does at the moment, but I use it in my Mathematica programs.

```mathematica
Paclet[
    Name -> "WolframLanguageForJupyter",
    Version -> "0.9.2",
    MathematicaVersion -> "11.2+",
    Extensions -> {
        {"Kernel", Context -> {"WolframLanguageForJupyter`"}},
        {"Documentation", Language -> "English"}
    }
]
```

_/!\ This example has not been tested yet, and may not work_

#### Source

The majority of my Mathematica knowledge comes from self-experimentation, and Wikipedia.

#### Other knowledge of Mathematica

1. Mathematica is a curly bracket language, and it does use semicolons at the end of each line.;

2. Mathematica uses the `*.m` file extension for normal use.

3. Mathematica uses the `*.nb` file extension for notebook programming

4. Mathematica is a language recognized by GitHub

5. Mathematica is not an open source programming language (it is proprietary) but it comes pre-installed on some Linux devices, such as the Raspberry Pi.

6. Mathematica was created by WolfRam

7. Mathematica is also known as WolfRam Mathematica

8. No other knowledge of Mathematica at the moment.

***

**File version:** `1 (2022, Monday, April 18th at 5:00 pm PST)`

***
