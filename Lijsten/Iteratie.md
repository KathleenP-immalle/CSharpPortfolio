# Een voorbeeld

```
static void Main(string[] args)
{
    List<Money> myMoney = new List<Money> {
        new Money{amount = 10, type="US"},
        new Money{amount = 20, type="US"}};
}

class Money
{
    public int amount { get; set; }
    public string type { get; set; }
}

foreach (var money in myMoney) {
    Console.WriteLine("Amount is {0} and type is {1}", money.amount, money.type);
}

```