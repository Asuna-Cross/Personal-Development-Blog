Today I'm continuing on with Ruby basics from TOP, I'm hoping to make it through at least two section today, if I'm able to do more then I will be happy.

For a change, I am up and active earlier on in the day compared to yesterday.

Today's first lesson is Input and Output. One of the lines in it did hit a bit of a slap, "code golf" describes the exsct mindset that I used to have back in my university days which caused me to fail C++ programming. At least I have grown since then and know that it's not worth it to fall into that pit again.

Went for a short walk between sessions. Onto conditional logic now.

So, an empty string won't automatically throw back a false, it depends on the rest of the logic behind it... This is going to be interesting.

if statements being written on the same line if it's all the one thing. I think I might avoid doing that at first and write it all out properly until I'm more comfortable so I don't end up in the state I used to be in during my university days.

"Spaceship Operator" seems like a fun and interesting thing to work on, and reminds me of my maths course.

Unless statements seem to be interesting, this is something to look into a bit more.

Times loops are a useful way of doing repeated things.

Onto my third section for today, Arrays. I should gather up my code snippets and put them into my cookbook.

Finished up the arrays exercises, all seem to be quite simple so far.

# Code snippet Notes
&& => And
|| => Or
! => Not
chomp => Gets rid of the new line when user enters data

Ternary Operator Syntax
conditional statement ? <execute if true> : <execute if false>

(1..5)      # inclusive range: 1, 2, 3, 4, 5
(1...5)     # exclusive range: 1, 2, 3, 4

Example of Times Loops
5.times do
  puts "Hello, world!"
end

upto and downto loops

5.upto(10) {|num| print "#{num} " }     #=> 5 6 7 8 9 10

10.downto(5) {|num| print "#{num} " }   #=> 10 9 8 7 6 5

array.new method
Array.new               #=> []
Array.new(3)            #=> [nil, nil, nil]
Array.new(3, 7)         #=> [7, 7, 7]
Array.new(3, true)      #=> [true, true, true]