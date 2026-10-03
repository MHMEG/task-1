namespace Firstapp
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("how many small carpet you clean it ? ");

           int x = Convert.ToInt32(Console.ReadLine()); ;
            int m = x * 25;
            Console.WriteLine("how many larg carpet you clean it ? ");
            int r = Convert.ToInt32(Console.ReadLine());
            int n = r * 35;
            Console.WriteLine($"so your total small carpet you clean it is {m}");
            Console.WriteLine($" and your total larg carpet you clean it {n} ");
            Console.WriteLine($"and your total cost plus the tax is  is {n + m + 6.6}");


        }
        
            }
    
        }

