# nvim-rspec
My rspec plugin to open and execute ruby test files

This is my first nvim plugin. I used it to make my life a little easier and learn Lua.

## Open test file
- get the current file path; (`:f` maybe?);
- change the path to add `rspec` and `_spec`;
- open/create the test file (`vim.cmd('e .. new_path')`)

## Execute test file
- get the current line and execute the test (`rspec path_spec.rb:current_line`);
- show icons to represent the result;
  - show error details;
  
- execute the whole test file
