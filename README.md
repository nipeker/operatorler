# operatorlerusing System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApplication6
{
    class Program
    {
        static void Main(string[] args)
        {
            //Atama ve İşlemli Atama
            int x = 3;
            int y = 3;
            y = y + 2;
            Console.WriteLine(y);
            y += 2;
            Console.WriteLine(y);
            y /= 1;
            Console.WriteLine(y);
            x *= 2;
            Console.WriteLine(x);

            //Mantıksal Operatörler
            // || veya , && ve  

            bool isSsuccess = true;
            bool isCompleted = false;

            if (isSsuccess && isCompleted)
                Console.WriteLine("perfect");

            if (isSsuccess || isCompleted)
                Console.WriteLine("great");

            // İlişkisel Operatörler
            // <,>, <=, >=,==
            Console.WriteLine("ilişkisel op");
            int a = 3;
            int b = 4;
            bool sonuc = a < b;
            Console.WriteLine(sonuc);
            sonuc = a > b;
            Console.WriteLine(sonuc);
            sonuc = a >= b;
            Console.WriteLine(sonuc);
            sonuc = a <= b;
            Console.WriteLine(sonuc);
            sonuc = a == b;
            Console.WriteLine(sonuc);
            sonuc = a != b;
            Console.WriteLine(sonuc);

            //Aritmetik Operatörler
            Console.WriteLine("aritmetik op");

            int sayı1 = 10;
            int sayı2 = 5;
            int sonuc1 = sayı1 / sayı2;
            Console.WriteLine(sonuc1);
            sonuc1 = sayı1 * sayı2;
            Console.WriteLine(sonuc1);
            sonuc1 = sayı1 + sayı2;
            Console.WriteLine(sonuc1);
            sonuc1 = ++sayı1;
            Console.WriteLine(sonuc1);
            // % mod alır
            int sonuc2 = 20 % 3;
            Console.WriteLine(sonuc2);
        }
    }
}
