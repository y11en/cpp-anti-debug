# cpp-anti-debug

a c++ library that offers debugger detection.

## getting started

these instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

literally download & include

you can then use

```
#include anti_debug.hpp

//will contain 0 if no debuggers etc. were found, anything else is the specific code for the detected problem
//see anti_debug.hpp for more information
int security_status = security::check_security();

if(security_status != 0) {
  std::cout << "security check was not successful." << std::endl;
}
```

## contributing
please create a pull request if you have made another check and want to include it or create an issue if you want me to add another check.

## versioning

we dont have that since im lazy and dont do updates.

## authors

* **Robert 'BaumFX'** - *initial work* - [website](https://baumfx.xyz) - [GitHub](https://github.com/BaumFX)

## license

its like 250 lines but dont say you made it, okay?
