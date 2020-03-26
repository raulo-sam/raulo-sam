# raulo-sam
Pasar grados farenheit a celsius

    class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("introdu<ca grados farhenheit");

            int f = int.Parse(Console.ReadLine());

            //far(f);

            Console.WriteLine(far(f));



            Console.WriteLine("introduzca grados celsius");

            int c = int.Parse(Console.ReadLine());

            //far(f);

            Console.WriteLine(cel(c));

        }

        public static float far(int f)
        {

            float c;
            c = (f - 32) / 1.8000f;
            Console.WriteLine();
            return c;
        }


        public static float cel(int c)
        {

            float f = c * 1.8000f + 32;

            return f;


        }
    }    
