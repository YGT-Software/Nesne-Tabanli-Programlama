# **`Abstract Class`'lar İle Çalışmak**

- `Interface`'ler ile `virtual` metotların birleşimi gibi düşünülebilir. Tamamen `inheritence` amacı ile kullanılır.

- `Abstract`, içi dolu olmayan `virtual` metotdur.

- `Abstract Class`'ların aynı `interface`'ler gibi `instance`'si oluşturulamaz.

- `Abstract Class`'lar birer `inheritence`'dir.

```csharp
abstract class Database
{
    public void Add()
    {
        Console.WriteLine("Added by Default");// Her yerde bu işlem aynı
    }
    public abstract void Delete();//Kullanıldığı yere göre değişiklik gösteriyor.
}
```
