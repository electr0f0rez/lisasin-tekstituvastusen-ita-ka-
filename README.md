# lisasin-tekstituvastusen-ita-ka-
parool

 //4 parool, if ja string andmetüüp
 Console.WriteLine("Programmi edasiseks tööks sisesta palun parool:");
 string password = Console.ReadLine();

 if (password == "simsalabin")
 {
     Console.WriteLine("Parool on õige, aarete laegas avaneb");
 }

 else if (password == "saatana" || password == "1234")
 {
     Console.WriteLine("Parool on sobimatu, palun mingi muu");
 }
 else
 {
     Console.WriteLine("Parool on vale, proovi uuesti");
 }
