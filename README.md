This is the code from the screencast Tic Tac Toe In Ruby Using Gosu (Annotated).  There are a few changes.  RSpec no longer supports the `its` syntax, so you need to include the gem `rspec-its` and put `require 'rspec/its'` in your spec file.

Another change is the `be_true` matcher is replaced with `be_truthy` and `be_false` with `be_falsey`.
