<!--
This file is auto-generated and will be re-generated every time the docs are updated.
To modify it, go to its source at https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/xcodebuild.rb
-->

# xcbuild


Builds the project using `xcodebuild`







xcbuild ||
---|---
Supported platforms | ios, mac
Author | @dtrenz



## 1 Example

```ruby
xcbuild
```





<hr />

## Documentation

To show the documentation in your terminal, run
```no-highlight
fastlane action xcbuild
```

<hr />

## CLI

It is recommended to add the above action into your `Fastfile`, however sometimes you might want to run one-offs. To do so, you can run the following command from your terminal

```no-highlight
fastlane run xcbuild
```

To pass parameters, make use of the `:` symbol, for example

```no-highlight
fastlane run xcbuild parameter1:"value1" parameter2:"value2"
```

It's important to note that the CLI supports primitive types like integers, floats, booleans, and strings. Arrays can be passed as a comma delimited string (e.g. `param:"1,2,3"`). Hashes are not currently supported.

It is recommended to add all _fastlane_ actions you use to your `Fastfile`.

<hr />

## Source code

This action, just like the rest of _fastlane_, is fully open source, <a href="https://github.com/fastlane/fastlane/blob/master/fastlane/lib/fastlane/actions/xcodebuild.rb" target="_blank">view the source code on GitHub</a>

<hr />

<a href="/actions/"><b>Back to actions</b></a>
