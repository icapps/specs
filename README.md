# iCapps specs

This is our iCapps Cocoapods specs repository.

## Setup

Add the iCapps specs repository to your Cocoapods installation by running the following command in your CLI:

    pod repo add icapps-spec git@github.com:icapps/specs.git

When you want to remove the iCapps specs repository from your Cocoapods installation you can run the following line:

    pod repo remove icapps-spec

## Add your pod

When you want to add a pod to the repository, you'll first have to start by creating your `.podspec` file. More information on how to do this can be found [here](https://guides.cocoapods.org/making/specs-and-specs-repo.html).

Add you pod to the iCapps specs repo with the following command:

    pod repo push icapps-specs ~/path_to/SomePod.podspec

## Use in your Podfile

Add the `source` line on top of your Podfile in order to install pods from this specs repo.

    source 'https://github.com/icapps/specs'

## License

Copyright (c) 2015 iCapps

MIT License

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
