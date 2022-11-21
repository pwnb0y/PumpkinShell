# Basics of Ruby-lang 
It will cover all of the syntax and terminologies of ruby language which is must require to start with scripting in ruby and work with Metasploit exploit development and so on.
 
 Note: This documentation is not for beginners at first you can learn from internet or books and then come here for only future revision.
## Introduction 
  Ruby is an open-source object-oriented scripting language invented in the mid-90s by Yukihiro Matsumoto.
  It is an interpreted, high-level, general-purpose programming language that supports multiple programming paradigms.

## Installation
For Kali
 ```sudo apt-get install ruby-full  ```

For Windows 
  [Ruby Installer]("https://rubyinstaller.org/downloads/")

## Hello World!
 ``` puts "Hello Ruby!" ```

 > save file with .rb extension.
## variables
A Variable is a special container that stores data values.

``` greet = "Good Evening!"
   puts ("Hello Elliot " + greet) # Hello Elliot Good Evening!
   puts "Hello Elliot #{greet}"  # Hello Elliot Good Evening!
 ```
There are four types of variables in Ruby:

   1. Local variables ``` name = "Elliot" ```
   2. Class variables ``` @@no_of_cert = 7 ```
   3. Instance variables ``` @jobrole= "Pentester" ```
   4. Global variables  ```  $global_var = "GLOBAL" ```


## Data Types 
A data type tells the compiler or interpreter how the programmer intends to use the data.

   * Numbers
   * Strings
   * Symbols
   * Hashes
   * Arrays
   * Booleans

## Math & Numbers
``` time = nil ``` means nothing in the time variable.

```
puts 5 / 9 # 0
puts 55 / 9 # 6
puts 2**3 # 8
puts 10 % 3 # 1
puts 4 % 10 # 4
```
## Strings
A string is a group of letters that represent a sentence or a word. Strings are defined by enclosing a text within single (') or double (") quote.

> Two strings can be concatenated using + sign in between them.
``` puts "Hello" + "Ruby" ```

> Multiplying a number string with a number will repeat the string as many times.
``` 3.times { puts "Hello!" }
    =begin  
     Hello!
     Hello!
     Hello!
    =end

    "3" * 7 # 3333333
 ```
## Hashes
```
    #!/usr/bin/ruby   
      
    data = {"Elliot" => "OSCP", "Alex" => "CEH", "Bob" => "CISSP"}   
    puts data["Elliot"]   
    puts data["Alex"]   
    puts data["Bob"]  
```
## Arrays
Ruby arrays are ordered collections of objects. They can hold objects like integer, number, hash, string, symbol or any other array. 
```
days = ["Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun"]   
puts days[0] # Mon     
puts days[10] # nothing will print here  
puts days[-2] # Sat    
puts days[2, 3] 
                # Wed
                # Thu
                # Fri 
puts days[1..7]
=begin  
Tue
Wed
Thu
Fri
Sat
Sun  
=end
```
## Booleans 
```online_status = true```
```script_state = false```

## Getting Input

## Control Statements
### if else 

```  if (condition)  
    //code to be executed  
    end
```

```  if(condition)  
        //code if condition is true  
    else  
    //code if condition is false  
    end 
```

```
 if(condition1)  
    //code to be executed if condition1is true  
 elsif (condition2)  
    //code to be executed if condition2 is true  
 else (condition3)  
    //code to be executed if condition3 is true  
 end   
 ```

### switch
```
#!/usr/bin/ruby   
print "Enter your day: "   
day = gets.chomp   
case day   
when "Tuesday"   
  puts 'Wear Red or Orange'   
when "Wednesday"   
  puts 'Wear Green'   
when "Thursday"   
  puts 'Wear Yellow'   
 when "Friday"   
  puts 'Wear White'   
 when "Saturday"   
  puts 'Wear Black'   
else   
  puts "Wear Any color"   
end 
```
## Ruby Comments
``` #This is single line comment.  ```

```    =begin  
        This  
        is  
        multi line  
        comment  
    =end  
```
## Ruby for Loop

## Regular Expressions

