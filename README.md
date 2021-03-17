# Summary

This project is intended to document Ruby items, including: 
1. course progression from various online resources
2. track my overall skill improvement
3. used as a source for "refreshers"
___
### **_Documentation References_**
- https://ruby-doc.org
___
### **_Courses_**
- (In Progress) https://www.linkedin.com/learning/ruby-essential-training-part-1-the-basics
___
### **_My Course Notes_**
- Object-Oriented Programming (OOP) language
- objects can be abstracted, have attributes, instance of a class
- variables are not objects but store a reference to an object and have a value (e.g. `first_name = "Kevin"`)
- variables can have scope indicators which have different characteristics, see table below

| Scope         | Indicator     |
| ------------- |:-------------:|
| Global        |`$variable`    |
| Class         |`@@variable`   |
| Instance      |`@variable`    |
| Local         |`variable`     |
| Block         |`variable`     |

- precision matters with numerical values, e.g. if you wanted to divide 10 by 3 and see an output with a decimal it must be `10.0 / 3` not `10 / 3` (float / integer or float / float)
- Number Methods include `abs` (absolute value), `round`, `floor` (rounds down), `ceil` (rounds up) 
- all Ruby files should end in `.rb`
- running files in CLI start with ruby, e.g. `ruby puts_command.rb`
- comments start with `#`
- Interactive Ruby Shell (IRB), interactive shell that can be used in CLI, activated with `irb` in CLI or `irb --simple-prompt` for simplified version, `quit` exits shell
- help/info can be found via `ri` command e.g. `ri String, useful when offline`
