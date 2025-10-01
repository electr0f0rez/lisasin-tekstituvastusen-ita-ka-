using System.Security.Cryptography;

namespace kontrolltõõ_01._10._2025
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //#
            // - küsib kasutajalt tema nimi ja sünniaasta
            Console.WriteLine("Mis on sinu nimi?");
            string nimi = Console.ReadLine();
           
            if (nimi ! == null)
            {
                Console.WriteLine("Tere " + nimi + "!");
            }
            else if (nimi == "")
            {
                Console.WriteLine("Kasutaja ei sisestanud oma nime");
            }
            
            Console.WriteLine(nimi + ",mis on sinu vanus");
            int kasutajavanus = int.Parse(Console.ReadLine());

            if (kasutajavanus > 0)
            {
                Console.WriteLine("Sa ei saa olla negatiivse vanusega!");
            }
            else
            {
                Console.WriteLine("Saad osta Monsterit");
            }



                //#
                // - Küsib praeguse temperatuuri
                Console.WriteLine("Sisesta praegune temperatuur");
            double temp = double.Parse(Console.ReadLine());

            if (temp < 0)
            {
                Console.WriteLine("põrgu jäätus");
            }
            else if (temp >= 0 && temp <= 10)
            {
                Console.WriteLine("päris külm on");
            }
            else if (temp >= 11 && temp <= 20)
            {
                Console.WriteLine("normaalne ilm");
            }
            else if (temp >= 21 && temp <= 30)
            {
                Console.WriteLine("kas läheb grillimiseks");
            }
            else if (temp >= 31 && temp <= 40)
            {
                Console.WriteLine("APPI; GLOBAALNE SOJENEMINE");
            }


            //#
            // - Küsib kasutajalt vaarikat, maasikat või apelsini
            Console.WriteLine("Kas sa tahad vaarikat, maasikat või apelsini?");
            string valik = Console.ReadLine();

            if (valik == "vaarikat")
            {
                Console.WriteLine("näe, varikas!");
            }
            else if (valik == "maasikat")
            {
                Console.WriteLine("maasikaski on!");
            }
            else if (valik == "apelsini")
            {
                Console.WriteLine("apelsini mul kashjuks ei ole :C");
            }
        }
    }
}
        






