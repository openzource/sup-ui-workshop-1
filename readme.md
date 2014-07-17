# Modern web UI workshop - day 1: CSS & SASS


### Setup
* Install a recent Ruby [https://www.ruby-lang.org/en/]
* Install SASS [http://sass-lang.com/install]
* Optionally install Compass [http://compass-style.org/install/]

### Usage
Checkout the repo
```sh
git clone https://github.com/rainopik/sup-ui-workshop-1.git
```

Update to first version to start a step-by-step walkthrough
```sh
git update tags/v01 
```

Move to the next version (and so on...):
```sh
git update tags/v02
...
```

Starting from v06, use this command to compile CSS from SCSS files:
```sh
sass -l -t expanded --watch sass:css
```

Starting from v11, use the following command to compile CSS:
```sh
compass watch
```


### License
(c) 2014 Rain Öpik <rain.opik@gmail.com>

This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See http://www.wtfpl.net/ for more details.
