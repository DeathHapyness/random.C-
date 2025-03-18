# random.C#
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace variavels
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //Console.Write("Digite sua idade:");
            //int idade=Convert.ToInt32(Console.ReadLine());

            //Console.Write("Digite sua altura:");
            //double altura=Convert.ToDouble(Console.ReadLine());

            //Console.WriteLine("Voce tem:" + idade + "anos e mede:" + altura + "m");

            Console.WriteLine("----------Finha de aluno do Senac----------");
            string nome, curso;
            double renda;
            bool resideEmSalto;
            Console.Write("Digite o nome do aluno:");
            nome = Console.ReadLine();

            Console.Write("Digite a renda familiar:");
            renda = Convert.ToDouble(Console.ReadLine());

            Console.Write("Digite o curso desejado:");
            curso = Console.ReadLine();

            Console.Write("reside em Sato? (true / false)");
            resideEmSalto = Convert.ToBoolean(Console.ReadLine());

            Console.WriteLine("Resumo do Cadastro");
            Console.WriteLine("Renda  familiar" + renda);
            Console.WriteLine("Curso desejado" + curso);
            Console.WriteLine("Residente de Salto" + resideEmSalto);



            Console.ReadKey();
        }
    }
}
