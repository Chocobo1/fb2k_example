## fb2k_example
A minimal project for developing foobar2000 component in VS2013 express


### Usage
1. Get [foobar2000 SDK](http://www.foobar2000.org/SDK) and extract it into `/lib/foobar2000_sdk` directory
2. Open `foo_test.sln`, select `OK` when asked whether to update compiler/libraries for old projects
3. Build `foo_test`!
4. `foo_test.dll` will be generated at `Debug/` or `Release/` directory depending on your configuration
5. To load the component in foobar2000, copy the generated dll to `foobar2000/components` directory

### Notes
* [Visual Studio 2013 & 2015 compatibility notice](http://www.hydrogenaud.io/forums/index.php?showtopic=108411)

### Useful references
* [foobar2000 development tutorial](http://yirkha.fud.cz/tmp/496351ef.tutorial-draft.html)
* [Resources for foobar2000 component developers](http://foosion.foobar2000.org/developers/)
