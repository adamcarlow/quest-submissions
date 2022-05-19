

   - Explain why we wouldn't call changeGreeting in a script.    
      - A script can only be used to view data.  

   - What does the AuthAccount mean in the prepare phase of the transaction?
      - This AuthAccount is the account which will need to approve the transaction.

   - What is the difference between the prepare phase and the execute phase in the transaction?
      - There is no difference as the transaction can be executed in the prepare phase, but it makes for better readable code to seperate the phases.


   - Add two new things inside your contract:
        A variable named myNumber that has type Int (set it to 0 when the contract is deployed)
        A function named updateMyNumber that takes in a new number named newNumber as a parameter that has type Int and updates myNumber to be newNumber
        
![image](https://user-images.githubusercontent.com/63122442/168476470-0f8866aa-8e7d-455e-8d5e-a7efb34a00e1.png)
        

   - Add a script that reads myNumber from the contract

![image](https://user-images.githubusercontent.com/63122442/168476524-aafbcae5-fca2-4fe4-b341-bd9f8d472438.png)


   - Add a transaction that takes in a parameter named myNewNumber and passes it into the updateMyNumber function. Verify that your number changed by running the script again.
  
![image](https://user-images.githubusercontent.com/63122442/168476673-4ca3bbec-7a64-4ed9-8c64-83be210da5e4.png)

![image](https://user-images.githubusercontent.com/63122442/168476697-d2ef891f-3e49-4ac6-9ea0-f7347c42077e.png)
