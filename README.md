# printing_quotes


The chop method will simply knock off the last character of the 
string, no matter what it is. Chomp will remove the ending input

Example:

puts "What is your name?" Rose Beatty
name = gets.chomp
puts "Your name is #{name}"
--> Your name is Rose Beatty


puts "What is your name?" Rose Beatty 
name = gets.chop
puts "Your name is #{name}"
--> Your name is Rose Beatt
