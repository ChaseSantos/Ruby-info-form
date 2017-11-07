print "What's your first name? "
first_name = gets.chomp
print "What's your last name? "
last_name=gets.chomp
answer.capitalise!
print "What city do you live in? "
city=gets.chomp
answer.capitalise!
print "What state do you live in? Make sure to shorten this answer! (EG IN for Infiana)"
state=gets.chomp
answer.upcase!
puts "Your name is #{first_name} #{last_name}!"
puts "You live in #{city}, #{state}!"
