# Active Support for RubyMotion aka MotionSupport

There is alot of active support stuff that you just dont need in the
motion rubyverse however there are extension that are more then useful.

Remember there is no require in motion land;

There is a dependency on bubblewrap at present as this is using their loader.

Code credit will goes to whomever did the original active support code;
this is just me moving it so it plays nice in RubyMotion; 

## Installation

```ruby
gem install motion_support
```

## Setup

In your Rakefile

```ruby
require 'motion_support'
```

The idea is that you can choose from a multiple modules so that you can easily choose which parts
are included at compile-time.

```ruby
require 'motion_support/all'
```

If you wish to only include the `concern`

```ruby
require 'motion_support/concern'
```

# Suggestions?

Do you have a suggestions? Feel free to open an
issue/ticket and tell us about what you are after. If you have a
helper you are using and are thinking that others might enjoy,
please send a pull request (with tests if possible).


