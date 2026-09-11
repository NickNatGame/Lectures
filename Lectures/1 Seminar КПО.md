из Лекции [[Lecture 1 КПО]]
Основное было на Лекции
```c#
public class Car
{
	private Engine engine;
	
	public Car(){
		Console.WriteLine("Car");
	}
}
```
```c#
public class Customer
{
	public Car? car(get; set;)
	
	public Customer()
	{
		car 
	}
}
```
```c#

```
```c#
class CarFactory
{
	private int counter = 0;
	private List<Car> cars = new();
	private List<Customer> customers = new();
	
	private AddCustomer(Custoemr customer){
		_customers.Add()
	}
}
```