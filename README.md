# Foreign Language Text Reader 1.4.1
- This fork aims to increase your study workflow speed when using FLTR for studying Japanese. It has the following modifications already implemented or planned to do so:
  - [x] Autofill new term fields with data from Jisho.org, so thanks to them! 
    - [ ] Restrict this function to Japanese.
  - [ ] Support for other languages (??)

# Links
- Jisho.org
  - Thanks for Jisho.org for providing an API so I didn't have to spend even more time writing this! Please check them out!
    - https://jisho.org/
- JsonPath
  - https://github.com/json-path/JsonPath
- OkHttp
  - https://github.com/square/okhttp

## Original Project
- Original website: https://sourceforge.net/projects/foreign-language-text-reader/
- Original tarball: https://sourceforge.net/projects/foreign-language-text-reader/files/
- Original Documentation: https://foreign-language-text-reader.sourceforge.io

# File structure
- bin/       - Contains the documentation PDF, and some demo data
- src/       - Contains the source code of FLTR
- makefile   - Builds FLTR (not tested)
- README.md  - Documentation

# How to build
- In case you don't trust this repo, you can build the final jar by yourself:
  - Using IntelliJ
    - Generate the artifact by moving the META-INF to the resources folder. 
    - For further instructions, please read https://www.jetbrains.com/help/idea/working-with-artifacts.html

## Installing (Linux)
- **IMPORTANT!!** Please proceed with caution because I haven't tested the install script after modifying the project
  - Run `sudo make install`
    - It installs to `/usr/local/` by default. Otherwise set the INSTALL\_PREFIX variable (and remember to run `sudo` with the `-E` option)

## LICENSE
Foreign Language Text Reader (FLTR) - A Tool for Language Learning.

Copyright © 2012-2021 FLTR Developers et al.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
________________________________________________________________________
