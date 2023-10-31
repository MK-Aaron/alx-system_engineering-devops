# 0x06. Regular expression
`Regex` `DevOps`

## Background Context
<p>For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.</p>

<p>Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the `//`:</p>

```
ron@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
sylvain@ubuntu$
ron@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
ron@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
ron@ubuntu$ ./example.rb 127.0.0.a
```
