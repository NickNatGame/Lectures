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
	
	private AddCustomer(Customer customer){
		_customers.Add(customer);
	}
	
	private AddCar(){
		counter++;
		_cars.Add(new Car())
	}
	
	public void SaleCar(){
		foreach(var customer in _customer){
			if(cusom)
		}
	}
}
```