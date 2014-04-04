pry-plus
========

Get up and going with a good set of pry tools right away.



Dependent Gems
--------------


### [pry-doc](http://banisterfiend.wordpress.com/)

Allows you to look into the Ruby builtin classes with the ? and $ commands.


  
- ? [].pop
  
- $ [].pop
  
- …etc.
  



### [pry-docmore](https://github.com/rking/pry-docmore/wiki)

Shows docs for dollar-vars and keywords


  
- show-docmores
  
- ? module
  
- ? $`
  



### [pry-byebug](https://github.com/deivid-rodriguez/byebug#readme)

An essential gem. Turns Pry into a steppable debugger. Ruby 2.0 compatible.


  
- Making the basic &quot;require&#39;pry&#39;;binding.pry&quot; from a script come alive.
  
- In conjunction with plymouth or pry-rescue, to explore failing tests.
  
- Following calls into other libs.
  



### [pry-stack_explorer](https://github.com/pry/pry-stack_explorer#readme)

Allows you to navigate the call stack.


  
- So many. TODO = document some.
  



### [pry-rescue](https://github.com/ConradIrwin/pry-rescue#readme)

Provides `Pry.rescue do … end` to capture any exceptions and start pry from the context of the source of the exception.


  
- Shortens write-run-debug cycles when exceptions are involved.
  
- Exploring causes of hard-to-replicate exceptions.
  
- `cd-cause` to source of exceptions in code run within Pry
  
- Rescues on test failure via `require` of `pry-rescue/minitest` and `pry-rescue/rspec`
  



### [bond](http://tagaholic.me/bond/)

An excellent tabcompletion gem. Having this dep enables new Pry stuff. Note that pry v0.9.10 doesn&#39;t have this feature, so you must use a repo version.


  
- `require &#39;x&lt;tab&gt;`
  
- `{asdf: 1, hjkl: 2}[:a&lt;tab&gt;`
  
- `Chain.of.calls.`&lt;tab&gt; # Old pry completion was generic in this case.
  



### [jist](https://github.com/ConradIrwin/jist#readme)

Replacement for the undermaintained `gist` gem.


  
- Improved implementation for Pry&#39;s `gist` command.
  
- Check out the `jist -h` output on the CLI, by the way.
  



