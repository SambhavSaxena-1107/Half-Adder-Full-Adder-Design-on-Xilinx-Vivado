module full_adder(    
       input a,b,cin,
       output sum,cout
 );
 wire s1,c1,c2;
        half_adder HA1(a,b,s1,c1);
        half_adder HA2(s1,cin,sum,c2);
     assign cout = c1 | c2;
endmodule
