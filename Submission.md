# Submissions

## Topic 1: Java

### Inheritance I

```Java
class Bird extends Animal
{
	void fly()
	{
		System.out.println("I am flying");
	}

    void sing()
    {
        System.out.println("I am singing");
    }
}
```

<img src="/assets/Inheritance I.png" alt="Inheritance 1" />

### Inheritance II

```Java
class Arithmetic {
    static int add (int a, int b) {
        return a + b;
    }
}

class Adder extends Arithmetic { }
```

<img src="/assets/Inheritance II.png" alt="Inheritance 2" />

### Interface

```Java
class MyCalculator implements AdvancedArithmetic {

    @Override
    public int divisor_sum(int n) { 
        int sum = 1;

        for (int i = 2; i <= n; i++) {
            if (n % i == 0) sum += i;
        }

        return sum;
    }

}
```

<img src="/assets/Interface.png" alt="Interface" />

### Method Overriding I

```Java
    @Override
    void getNumberOfTeamMembers() {
        System.out.println("Each team has 11 players in " + getName());
    }
```

<img src="/assets/Method Overriding I.png" alt="Method Overriding 1" />

### Method Overriding II (Super Keyword)

```Java
String temp = super.define_me(); 
```

<img src="/assets/Method Overriding II.png" alt="Method Overriding 2" />



