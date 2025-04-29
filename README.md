# comp2396--assignment-3-a-vending-machine-which-vends-soft-drinks-that-accept-coins-only-solved
**TO GET THIS SOLUTION VISIT:** [COMP2396- Assignment 3-a vending machine, which vends soft drinks, that accept coins only Solved](https://www.ankitcodinghub.com/product/comp2396-assignment-3-a-vending-machine-which-vends-soft-drinks-that-accept-coins-only-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;49825&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP2396- Assignment 3-a vending machine, which vends soft drinks, that accept coins only Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Description:

Consider a vending machine, which vends soft drinks, that accept coins only. The vending machine allows customers to insert coins, purchase a product and reject inserted coins. In this assignment, you need to build a system to simulate the operations of vending soft drinks in a vending machine. Please read this assignment sheet carefully before starting your work.

Typical vending machine consist of these components:

• A Coin Slot allows customers to insert coins into the machine. It also serves as temporality storage for inserted coins and accumulates the amount of face value.

• A button to reject all inserted coins.

• A Coin Changer stores coins for giving change. Change is the money that is returned to the customer who has paid for the product that costs less than the amount that the customer has given.

• A Soft Drink Slot holds the same products of soft drinks in a column. When a transaction is made, the slot will drop a can of drink into the dispenser.

Standard workflow for vending a soft drink in a vending machine is as follow:

1. The customer inserts coins into the Coin Slot.

2. The customer selects a product.

3. If the customer has inserted enough amount of money for the product, the vending machine firstly drops the product and return change (if necessary). Then, all coins in the Coin Slot are moved to the Coin Changer.

Task: Implement this system. Below shows a simple run-down.

A partial completed VendingMachine class is provided as follows

import java.util.ArrayList;

public class VendingMachine {

private ArrayList coinChanger; private ArrayList coinSlot;

private ArrayList softDrinkSlots;

public VendingMachine() { coinChanger = new ArrayList(); coinSlot = new ArrayList();

softDrinkSlots = new ArrayList();

}

public void addCoinToCoinChanger(Integer c) { coinChanger.add(c);

}

public void addSoftDrinkSlot(SoftDrinkSlot s) { softDrinkSlots.add(s);

}

/* You may add other non-static properties and methods */

}

You must not modify the parameter lists of the constructor, addCoinToCoinChanger() and addSoftDrinkSlot() as we will use these methods to initiate the vending machine in test cases evaluation.

The SoftDrinkSlot class is provided as follow

public class SoftDrinkSlot {

private String name; private int price;

private int quantity;

public SoftDrinkSlot(String name, int price, int quantity) {

this.name = name; this.price = price; this.quantity = quantity;

}

/* You may add other non-static properties and methods */

}

You must not modify the parameter lists of the constructor as we will use it in test cases evaluation.

The system should be operated via commands (except initiating the vending machine), which is, every time we want to operate the vending machine, an instance of Command object should be created. The Command object will be the interface for the main program to perform actions on the Vending Machine. Different types of commands are handled by different specific classes that inherit the Command class. The Command class is defined as follows

public class Command { public String execute(VendingMachine v, String cmdPart){

String result = null;

return result;

}

}

You need to implement 3 commands for the system, namely CmdInsertCoin, CmdRejectCoins and CmdPurchase. These commands should inherit the Command class. Each Command class perform specific actions to the vending machine in the execute() method. The method takes the VendingMachine object and a command content in String as the input parameters. After performing actions, the method should return the result of the command in String.

1. CmdInsertCoin – Insert a coin

2. CmdRejectCoins – Reject all coins from Coin Slot

3. CmdPurchase – Vend a can of soft drink to the customer. When giving a change to the customer, the machine should find the minimum number of coins in the Coin Changer to make the change.

For example, CmdInsertCoin inherit Command class and perform actions in the execute() method:

public class CmdInsertCoin extends Command {

@Override

public String execute(VendingMachine v, String cmdPart) {

Integer coin = Integer.valueOf(cmdPart);

// Add the coin to Coin Slot

return /*…*/;

}

}

You also need to add handling for the following special cases, but you can assume no more than one special case would happen simultaneously in our test cases.

• Insufficient amount of money to buy the drink.

• The drink is out of stock

• Not enough coins in Coin Changer for giving a particular amount of change to the customer.

Notes:

1. The listing of coins should be sorted by the face value ascendingly.

2. All coins are in dollar unit ($1, $2, $5, $10), no need to deal with cents.

3. When preparing coins for a change, the vending machine looks for coins in the Coin Changer only.

4. The system should find the minimum number of coins for preparing the change. For example, if one $5 coin is available, then the $5 coin should be selected instead of selecting $1, $2 and $2 coins.

5. You are free to add other classes that help you to implement the system. You can upload up to 50 files to Moodle.

6. You must NOT declare any static variable in your program as a static variable will disrupt our evaluation system.

7. If you failed to pass a test case, Moodle only shows you the last line of expected output and program output.
