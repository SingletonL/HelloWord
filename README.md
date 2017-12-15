# HelloWord
#My First Repository

using System;
using System.Collections.Generic;

namespace firstcore
{
    class Program
    {
        static void Main(string[] args)
        {
            var names = new List<string>{"<name>","Ana","Felipe"};
	      		foreach(var name in names)
	      		{
	      			Console.WriteLine($"Hello {name.ToUpper()}!");
	      		}
        }
    }
}

