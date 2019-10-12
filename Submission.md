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

![Inheritance I](/assets/Inheritance I.png)

### Inheritance II

```Java
class Arithmetic {
    static int add (int a, int b) {
        return a + b;
    }
}

class Adder extends Arithmetic { }
```

![Inheritance II](/assets/Inheritance II.png)

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

![Interface](/assets/Interface.png)

### Method Overriding I

```Java
    @Override
    void getNumberOfTeamMembers() {
        System.out.println("Each team has 11 players in " + getName());
    }
```

![Method Overriding I](/assets/Method Overriding I.png)

### Method Overriding II (Super Keyword)

```Java
String temp = super.define_me(); 
```

![Method Overriding II](/assets/Method Overriding II.png)



