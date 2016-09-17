# Quiz_887342
US_states = 

	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
	
US_states.each { |as,ps|
  
    if ps[1]=="T" || ps[1] == "N"
        puts "------------>"
      puts ps
    end 
 
}
  puts "------------>"
 puts  US_states.sort { |x,y| y <=> x } 
  
 puts "------------>"
 
 US_states.each { |as,ps|
  
   if (as[0]=="A" || as[0] == "E" || as[0] == "I" || as[0] == "O" || as[0] == "U")&&(as[as.length-1] == "a" || as[as.length-1] == "e" || as[as.length-1] == "i" || as[as.length-1] == "o" || as[as.length-1] == "u") 
    puts as 
    end
}
 puts "------------>"

require 'prime'
print "Enter number : "
n = gets.chomp.to_i
Prime.each(n) do |prime|
  p prime 
end

ทำเสร็จถึงข้อ 2




