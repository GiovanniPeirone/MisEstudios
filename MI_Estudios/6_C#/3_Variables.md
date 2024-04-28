
	string hola = "hola mundo";



El tipo de dato dynamic te permitr mete cualquie cosa y camviarlo ej


namespace HelloWorld
{
    class Program
    {
        static void Main(string[] args)
        {
            dynamic a = 1;
            Console.WriteLine(a);
            a = "hola mundo";
            Console.WriteLine(a);
        }
    }
}

