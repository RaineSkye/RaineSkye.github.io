---
layout: post
title:      "When to use Hashes vs Arrays"
date:       2018-12-28 19:40:30 +0000
permalink:  when_to_use_hashes_vs_arrays
---


Hashes and arrays are two ways to organize data such as strings, integers, or symbols or a combination of these data in Ruby.

An array can be handy for small-ish lists.

*An array contains data in brackets [ ] *

examples:  

shopping_list = [ ]

shopping_list = [ "mango", "honey", "eggs"]   

*Array data is arranged by index number, starting at index zero (0).  You'll need to keep track of the location (index) of the data in order to access it.  *

shopping_list[0]
=> "mango"

shopping_list[1]
=> "honey"

So you can see that if you have a bigger list and need to organize data either by categories or keep count of many similar items, or for ease of accessibility to the stored data, an array might not be the answer. 

This is where the Hash comes in.  Hashes can be very useful for giant lists where you want to be able to easily retrieve the data later on.    

A hash is an  key-value pairs, contained in curly braces { } and separated by commas . You can retrieve any item by calling it's key, which will pull up its associative value.

new_hash = { }
=> {}

names_of_guests_alphabetized = {"a" => 23, "b" => 5, "c" => 63, "d" => 41, "e" =>7}
=> {"a"=>23, "b"=>5, "c"=>63, "d"=>41, "e"=>7}

paper_shopping = { "bathroom" => "facial tissue", "kitchen" => "paper towels", "office" => "printer paper"}






