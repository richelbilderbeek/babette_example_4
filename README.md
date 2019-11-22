# babette_example_4

Branch   |[![Travis CI logo](pics/TravisCI.png)](https://travis-ci.org)                                                                                           |[![AppVeyor logo](pics/AppVeyor.png)](https://appveyor.com)                                                                                               
---------|--------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
`master` |[![Build Status](https://travis-ci.org/richelbilderbeek/babette_example_4.svg?branch=master)](https://travis-ci.org/richelbilderbeek/babette_example_4) |[![Build status](https://ci.appveyor.com/api/projects/status/or81kg7cdkljc56i/branch/master?svg=true)](https://ci.appveyor.com/project/richelbilderbeek/babette-example-4/branch/master)
`develop`|[![Build Status](https://travis-ci.org/richelbilderbeek/babette_example_4.svg?branch=develop)](https://travis-ci.org/richelbilderbeek/babette_example_4)|[![Build status](https://ci.appveyor.com/api/projects/status/or81kg7cdkljc56i/branch/develop?svg=true)](https://ci.appveyor.com/project/richelbilderbeek/babette-example-4/branch/develop)

A [babette example](https://github.com/richelbilderbeek/babette_examples).

## Example #4: Relaxed clock log normal

![Example #4: Relaxed clock log normal](pics/rln_2_4.png)

```{r}
posterior <- bbt_run(
  "my_alignment.fas",
  clock_model = create_rln_clock_model()
)
```

All other parameters are set to their defaults, as in BEAUti.

## Result

![](result.png)

