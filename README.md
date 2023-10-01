# dom-rabota
 //ZADACHA 1
            int decnumber = 384;
            string binnumber = Convert.ToString(decnumber, 2);
            Console.WriteLine(decnumber+"(10)="+binnumber+"(2)");
//ZADACHA 2
string hexnumber = "FB4";
            int decnumber = Convert.ToInt32(hexnumber, 16);
            Console.WriteLine(hexnumber+"(16)="+decnumber+"(10)");
//Zadacha 3
string binnumber = "111011000";
            int decnumber = Convert.ToInt32(binnumber, 2);
            string hexnumber = Convert.ToString(decnumber, 16);
            Console.WriteLine(binnumber+"(2)="+hexnumber.ToUpper()+"(16)");
