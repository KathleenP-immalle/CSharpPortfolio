# Een voorbeeld

Vergeet niet te initialiseren!

```
static void Main(string[] args)
{
    List<Money> myMoney = new List<Money> {
        new Money{amount = 10, type="EU"},
        new Money{amount = 20, type="EU"}};
}

class Money
{
    public int amount { get; set; }
    public string type { get; set; }
}

```

## For

```

for (var i = 0; i < myMoney.Count; i++)
{
    System.Console.WriteLine("{0}", myMoney[i]);
}

```

## Foreach

```

foreach(var money in myMoney) {
    Console.WriteLine("Amount is {0} and type is {1}", money.amount, money.type);
}

```