# Ex.No:3(D)    INTERFACE 

## QUESTION:
You are programming bots that analyze weather data. Each bot must implement a common interface and give a prediction.

## AIM:
To implement an interface-based design in Java by creating a WeatherBot interface and implementing its predict() method in the SunBot and RainBot classes to provide weather predictions based on temperature.

## ALGORITHM :
1. Start the program and open a Scanner object for taking user inputs.

2. Define an interface named WeatherBot containing an abstract method predict(int temp).

3. Implement the interface in SunBot and RainBot classes with their respective temperature logic.

4. Read the temperature value and the bot type choice (1 for SunBot, 2 for RainBot) from the user.

5. Instantiate the chosen bot class dynamic object using the interface reference variable and call predict().

6. Print the final prediction string ("HOT", "MODERATE", "COLD", or "WARM") and stop




## PROGRAM:
 ```
/*
Program to implement a Interface using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013 
*/
```

## SOURCE CODE:

```import java.util.*;
interface WeatherBot{
    void predict(int temp);
}
class SunBot implements WeatherBot{
    public void predict(int temp){
        if(temp>30){
            System.out.println("HOT");
        }else{
            System.out.println("MODERATE");
        }
    }
}
class RainBot implements WeatherBot{
    public void predict(int temp){
        if(temp<20){
            System.out.println("COLD");
        }else{
            System.out.println("WARM");
        }
    }
}
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int temp=sc.nextInt();
        int c=sc.nextInt();
        
        if(c==1){
            WeatherBot bot = new SunBot();
            bot.predict(temp);
        }else{
            WeatherBot bot = new RainBot();
            bot.predict(temp);
        }
    }
}
```





## OUTPUT:

<img width="311" height="145" alt="image" src="https://github.com/user-attachments/assets/2b8b8048-f05b-4362-acd1-3b4f6b112de5" />


## RESULT:
Thus the program to implement interface program for given input was executed successfuly.
