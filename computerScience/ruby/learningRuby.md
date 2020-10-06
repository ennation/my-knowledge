# Learning Ruby
## Notes
This page will not follow my usual format, as these are my personal learning notes

### General Notes

* if statement can be used with variables to determine if they are nil or not
* unless = !if
* This is a cool way to say "only if condition A is true *and* condition B is false
	* print "We're using plastic 'cause we don't have glass." if plastic_cup unless glass_cup
* You can use if statements in assignments! 
		
		at_hotel = true
	
		email = if at_hotel
		
          "why@hotelambrose.com"
          
        else
        
          "why@drnhowardcham.com"
          
        end
        
* Almost everything in Ruby is an object
	* if statements aren't really. `self` isn't really. other than that, though, yeah everything's an object.

## Links
* [Ruby Koans](http://rubykoans.com) - An awesome set of exercises for learning
* [Why's Poignant Guide to Ruby](https://poignant.guide/book/chapter-1.html) - A humorous and fun guide to learning Ruby
* [Ruby for Beginners](http://ruby-for-beginners.rubymonstas.org/index.html) - Relatively un-cool but very robust guide to the basics