# rustcodeuse std::io;
fn main(){
println!("HEY WELCOME TO SYR TOURS AND TRAVELS: \n\n");    
//println!("EMIRATES INFORMATION");
//println!("Emirates is an airline based in Garhoud, Dubai, United Arab Emirates. The airline is a subsidiary of The Emirates Group, which is owned by the government of Dubai's Investment Corporation of Dubai.
//Destinations: 161");
//println!("Bag information: In economy, to/from Americas, two bags free. To other destinations, 20kg free, additional allowance depending on route. More Emirates bag information");

//println!("PIA INFORMATION");
//println!("Pakistan International Airlines is the national flag carrier of Pakistan. Its main hub is Karachi's Jinnah International Airport, while Allama Iqbal International Airport in Lahore, and Islamabad International Airport serve as secondary hubs");
//println!("BAGAGE INFORMATION ");
//println!("Bag information: In economy, within Pakistan, 1st bag free, 2nd bag Rs 3,000. To other destinations, 1st bag free, 2nd bag varies by itinerar");


//println!("QATAR INFORMATION");
//println!("Qatar Airways Company Q.C.S.C., operating as Qatar Airways, is the state-owned flag carrier of Qatar.");
//println!("BAGAGE INFORMATION");
//println!("In economy, to/from Americas, two bags free. To other destinations, 30kg free, additional allowance depending on route");

println!("1.AMERICA");
println!("2.CANADA");
println!("3.ENGLAND");
println!("4.GERMANY");
println!("5.FRANCE");
println!("6.DUBAI");
println!("7.SAUDI ARABIA");
println!("8.SINGAPORE");
println!("9.MALAYSIA");
println!("10.THAILAND");
println!("11.AUSTRALIA");
println!("12.CHINA");
println!("13.BAHRAIN");
println!("14.ITALY");
println!("15.NEWZELAND");
println!("16.TURKEY");
println!("17.IRAN");
println!("18.SOUTH AFRICA");
println!("19.SYRIA");
println!("20.SWITZERLAND");

     let mut press = String::new(); 
     io::stdin().read_line(&mut press)  
     .expect("Failed to read line"); 
     let _press: u32 = press.trim().parse()        
     .expect("Please type a number for car information");     

      if _press==1
      {
       america();
      } 
       else if _press ==2
       {
       canada ();  
       }
       else if _press==3
       {
        england ();
       }
       else if _press==4
       {
         germany();
       }
       else if _press==5
       {
         france();
       }
       else if _press==6
       {
         dubai();
       }
       else if _press==7
       {
         saudi_arabia();
       }
       else if _press==8
       {
         singapore();
       }
       else if _press==9
       {
         malaysia();
       }
       else if _press==10
       {
         thailand();
       }
       else if _press==11
       {
         australia();
       }
       else if _press==12
       {
         china();
       }
       else if _press==13
       {
         bahrain();
       }
       else if _press==14
       {
         italy();
       }
       else if _press==15
       {
        newzeland ();
       }
       else if _press==16
       {
         turkey();
       }
       else if _press==17
       {
         iran();
       }
       else if _press==18
       {
         south_africa();
       }
       else if _press==19
       {
         syria();
       }
         else if _press==20
        {
          switzerland();
        }


      }



   fn america () {
   println!("USA TOURISM\n");
   println!("In the U.S tourism is among the three largest employers in 29 states, employing 7.3 million in 2004, to take care of 1.19 billion trips tourists took in the U.S. in 2005. As of 2018, New York City is the most visited destination in the United States, followed by Los Angeles, Orlando, Las Vegas, and Chicago \n\n");
   println!("\nPlease Tell Us About Your Details first :)");

     println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
        .expect("Failed to read line"); 

        println!("Enter Your CNIC Number:");
        let mut number=String::new();
        io::stdin().read_line(&mut number)
         .expect("Failed to read line"); 
        let _number:i128=number.trim().parse().unwrap();


     println!("Enter Your seat Number:");
     let mut number= String::new(); 
     io::stdin().read_line(&mut number)  
     .expect("Failed to read line"); 
     let number: u32 = number.trim().parse()        
     .expect("failed information");

     println!("Now Please Select Tickets:\n");

   println!("TICKET: 1 for  ECONOMY CLASS 120000rs,");
   println!("TICKET: 2 for  BUSINESS CLASS 2500000 rs");
   println!("TICKET: 3 for  FIRST CLASS 400000 rs");
   let mut input = String::new(); 

   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("failed read line");     

   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nyour seat number is {}",_number);
     println!("\nYOU HAVE SELECTED ECONOMY CLASS");
     println!("\nFLIGHT A380: departure time : 18:00 pm ");
     println!("\nTHE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");

   }
  else if _input==2
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number); 
           println!("\nYour seat number is {}",_number); 
          println!("\nYOU HAVE SELECTED BUSINESS CLASS");
          println!("\nTHE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",_number);
          println!("\nYOU HAVE SELECTED FIRST CLASS");
          println!("\nTHE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 

  }  

 fn canada () {
  println!("Canada has a large domestic and foreign tourism industry. The second largest country in the world, Canada's incredible geographical variety is a significant tourist attractor. Much of the country's tourism is centred in the following (busiest) regions");
  println!("\nFLIGHT A380: Departure time : 18:00 pm ");


       println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 


       println!("Now Please Select Tickets:\n");

   println!("TICKET: 1 for ECONOMY CLASS 120000rs,");
   println!("TICKET: 2 for BUSINESS CLASS 2500000 rs");
   println!("TICKET: 3 for FIRST CLASS 400000 rs");
   let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     

   if _input == 1
   {
  println!("Enter Your Name: ");
let mut name =String::new();
io::stdin().read_line(&mut name)
 .expect("Failed to read line"); 

println!("Enter Your CNIC Number:");
let mut _number=String::new();
io::stdin().read_line(&mut _number)
 .expect("Failed to read line"); 
let _number:i128=_number.trim().parse().unwrap();


          println!("your name is {}",name);
          println!("your cnic number is {}",number);
          println!("Your seat number is {}",number);
          println!("YOU HAVE SELECTED ECONOMY CLASS");
          println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
          println!("\nyour name is {}",name);
          println!("\nyour cnic number is {}",number);
          println!("\nYour seat number is {}",value);
          println!("\nYOU HAVE SELECTED BUSINESS CLASS");
          println!("\nTHE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nyour name is {}",name);
          println!("\nyour cnic number is {}",number);
          println!("\nYour seat number is {}",value);
          println!("\nYOU HAVE SELECTED FIRST CLASS");
          println!("\nTHE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}

fn england(){
  println!("England is a country that is part of the United Kingdom.[5][6][7] It shares land borders with Wales to the west and Scotland to the north. The Irish Sea lies west of England and the Celtic Sea to the southwest. England is separated from continental Europe by the North Sea to the east and the English Channel to the south");
  println!("FLIGHT A430, Departure time : 20:00 pm ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 




       println!("Now Please Select Tickets:\n");


  println!("TICKET: 1 for  ECONOMY CLASS 120000rs,");
   println!("TICKET: 2 for  BUSINESS CLASS 2500000 rs");
   println!("TICKET: 3 for  FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
             println!("\nYour Name is: {}",name);
             println!("\nYour CNIC Number Is: {}",number);
             println!("\nYour seat number is {}",value);

             println!("YOU HAVE SELECTED FIRST CLASS");
             println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 

} 

fn germany() {
println!("Germany (German: Deutschland, German pronunciation: [ˈdɔʏtʃlant]), officially the Federal Republic of Germany (German: Bundesrepublik Deutschland, About this soundlisten (help·info)),[h] is a country in Central and Western Europe");
println!("\nFLIGHT A430, Departure time : 22:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

println!("TICKET:1 for ECONOMY CLASS 120000rs,");
println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

           println!("YOU HAVE SELECTED FIRST CLASS");
           println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn france(){
  println!("YOU HAVE SELECTED FRANCE");
  println!("\nFLIGHT A430, Departure time : 24:00 am ");


println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 




       println!("Now Please Select Tickets:\n");


  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {

           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

           println!("YOU HAVE SELECTED FIRST CLASS");
           println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 

}

fn dubai (){
  println!("YOU HAVE SELECTED DUBAI");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 
       println!("Now Please Select Tickets:\n");


  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {

            println!("\nYour Name is: {}",name);
            println!("\nYour CNIC Number Is: {}",number);
            println!("\nYour seat number is {}",value);


          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 

}
fn saudi_arabia(){
  println!("YOU HAVE SELECTED SAUDI ARABIA");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 
       println!("Now Please Select Tickets:\n");

  println!("FLIGHT A430, Departure time : 24:00 am ");
  println!("TICKET:1 for  ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);


         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn singapore(){
  println!("YOU HAVE SELECTED SINGAPORE");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("FLIGHT A430, Departure time : 24:00 am ");
  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for  FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

      println!("\nYour Name is: {}",name);
      println!("\nYour CNIC Number Is: {}",number);
      println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {

            println!("\nYour Name is: {}",name);
            println!("\nYour CNIC Number Is: {}",number);
            println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

           println!("YOU HAVE SELECTED FIRST CLASS");
           println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn malaysia(){
  println!("\nYOU HAVE SELECTED MALAYSIA ");
  println!("\nFLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

       println!("\nYour Name is: {}",name);
       println!("\nYour CNIC Number Is: {}",number);
       println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {      

          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn thailand(){
  println!("YOU HAVE SELECTED THAILAND");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn australia(){
  println!("YOU HAVE SELECTED AUSTRALIA");
  println!("FLIGHT A430, Departure time : 24:00 am ");

  println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {  
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

             println!("\nYour Name is: {}",name);
             println!("\nYour CNIC Number Is: {}",number);
             println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn china(){
  println!("YOU HAVE SELECTED CHINA");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 


       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

        println!("\nYour Name is: {}",name);
        println!("\nYour CNIC Number Is: {}",number);
        println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
               println!("\nYour Name is: {}",name);
               println!("\nYour CNIC Number Is: {}",number);
               println!("\nYour seat number is {}",value);


          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn bahrain(){
  println!("YOU HAVE SELECTED BAHRAIN");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {


    println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);


     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn syria(){
  println!("YOU HAVE SELECTED SYRIA");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       { 
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn italy(){
  println!("YOU HAVE SELECTED ITALY ");
  println!("FLIGHT A430, Departure time : 24:00 am ");
  println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 
       println!("Now Please Select Tickets:\n");


  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
            println!("\nYour Name is: {}",name);
            println!("\nYour CNIC Number Is: {}",number);
            println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn newzeland(){
  println!("YOU HAVE SELECTED NEWZELAND");
  println!("FLIGHT A430, Departure time : 24:00 am ");
  println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nyour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn turkey(){
  println!("YOU HAVE SELECTED TURKEY");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {  
     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
          println!("\nYour Name is: {}",name);
          println!("\nYour CNIC Number Is: {}",number);
          println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

        println!("\nYour Name is: {}",name);
        println!("\nYour CNIC Number Is: {}",number);
        println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn iran(){
  println!("YOU HAVE SELECTED IRAN");
  println!("FLIGHT A430, Departure time : 24:00 am ");

println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 

       println!("Now Please Select Tickets:\n");

  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {

     println!("\nYour Name is: {}",name);
     println!("\nYour CNIC Number Is: {}",number);
     println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {
            println!("\nYour Name is: {}",name);
            println!("\nYour CNIC Number Is: {}",number);
            println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


}
fn south_africa(){
  println!("YOU HAVE SELECTED SOUTH AFRICA");
  println!("FLIGHT A430, Departure time : 24:00 am ");

  println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 


       println!("Now Please Select Tickets:\n");
  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     
   //println!("YOU HAVE SELECTED ECONOMY CLASS");
   if _input == 1
   {
      println!("\nYour Name is: {}",name);
      println!("\nYour CNIC Number Is: {}",number);
      println!("\nYour seat number is {}",value);

     println!("YOU HAVE SELECTED ECONOMY CLASS");
     println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
   }
  else if _input==2
       {

           println!("\nYour Name is: {}",name);
           println!("\nYour CNIC Number Is: {}",number);
           println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {

        println!("\nYour Name is: {}",name);
        println!("\nYour CNIC Number Is: {}",number);
        println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 
 }

  fn switzerland() {
  println!("YOU HAVE SELECTED SWITZERLAND ");
  println!("FLIGHT A430, Departure time : 24:00 am ");
  println!("Enter Your Name: ");
       let mut name =String::new();
       io::stdin().read_line(&mut name)
       .expect("Failed to read line"); 



       println!("Enter Your CNIC NUMBER: ");
       let mut number =String::new();
       io::stdin().read_line(&mut number)
       .expect("Failed to read line"); 


       println!("Enter Your Seat number: ");
       let mut value =String::new();
       io::stdin().read_line(&mut value)
       .expect("Failed to read line"); 
       println!("Now Please Select Tickets:\n");


  println!("TICKET:1 for ECONOMY CLASS 120000rs,");
  println!("TICKET:2 for BUSINESS CLASS 2500000 rs");
  println!("TICKET:3 for FIRST CLASS 400000 rs");
  let mut input = String::new(); 
   io::stdin().read_line(&mut input)  
   .expect("Failed to read line"); 
   let _input: u32 = input.trim().parse()        
   .expect("Please type a number for car information");     

       if _input == 1
      {

        println!("\nYour Name is: {}",name);
        println!("\nYour CNIC Number Is: {}",number);
        println!("\nYour seat number is {}",value);

       println!("YOU HAVE SELECTED ECONOMY CLASS");
       println!("THE PRICE OF ECONOMY CALSS TICKET IS 120000 rs only ");
      }
      else if _input==2
       {

        println!("\nYour Name is: {}",name);
        println!("\nYour CNIC Number Is: {}",number);
        println!("\nYour seat number is {}",value);

          println!("YOU HAVE SELECTED BUSINESS CLASS");
          println!("THE PRICE OF BUSINESS CLASS IS 2500000 rs only ");
       }
       else if _input==3
       {
         println!("\nYour Name is: {}",name);
         println!("\nYour CNIC Number Is: {}",number);
         println!("\nYour seat number is {}",value);

         println!("YOU HAVE SELECTED FIRST CLASS");
         println!("THE PRICE OF FIRST CLASS IS 3000000 rs only");
       } 


     }
