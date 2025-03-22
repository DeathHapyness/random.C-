// produtos 
int coca = 7;
int pepsi = 9;
int fanta = 10;
int produto = 1;
int quantidade;

while (produto != 0)
{
    Console.WriteLine("Escolha o número do produto: \n1 - Coca\n2 - Pepsi\n3 - Fanta \n0 para-sair");
    produto = Convert.ToInt32(Console.ReadLine());

    

    if (produto == 1)
    {
        Console.WriteLine("Digite a quantidade de produto que você deseja:");
        quantidade = Convert.ToInt32(Console.ReadLine());
        if (quantidade <= coca)
        {

            Console.WriteLine("Você pediu Coca.");
            Console.WriteLine("Estoque restante: " + (coca = coca - quantidade));
        }
        else
        {
            Console.WriteLine("Quantidade indisponivel.");
        }
    }
    else if (produto == 2)
    {
        Console.WriteLine("Digite a quantidade de produto que você deseja:");
        quantidade = Convert.ToInt32(Console.ReadLine());
        if (quantidade <= pepsi)
        {

            Console.WriteLine("Você pediu Pepsi.");
            Console.WriteLine("Estoque restante: " + pepsi);
        }
        else
        {
            Console.WriteLine("Quantidade indisponivel.");
        }
    }
    else if (produto == 3)
    {
        Console.WriteLine("Digite a quantidade de produto que você deseja:");
        quantidade = Convert.ToInt32(Console.ReadLine());
        if (quantidade <= fanta)
        {

            Console.WriteLine("Você pediu Fanta.");
            Console.WriteLine("Estoque restante: " + fanta);
        }
        else
        {
            Console.WriteLine("Quantidade indisponivel.");
        }
    }
    else
    {
        Console.WriteLine("Pedido finalizado.");
    }
}
Console.ReadKey();
