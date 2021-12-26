def income_tax(income):
    
    taxable_income = 0
    tax_amt = 0
    
    if income in range(0,250000):
        tax = 0
        taxable_income = 0
        
    else:
        pass
        
    if income in range(250000,500000):
        taxable_income = income - 250000
        tax_amt = 5/100*taxable_income
        
    else:
        pass
       
    
    if income in range(500000,750000):
        taxable_income = income - 500000
        tax_amt = 10/100*taxable_income + 12500
        
    else:
        pass
    
    if income in range(750000,1000000):
        taxable_income = income - 750000
        tax_amt = 15/100*taxable_income + 37500
        
    else:
        pass
    
    if income in range(1000000,1250000):
        taxable_income = income - 1000000
        tax_amt = 20/100*taxable_income + 75000
        
    else:
        pass
    
    if income in range(1200000,1500000):
        taxable_income = income - 1250000
        tax_amt = 25/100*taxable_income + 125000
        
    else:
        pass
    
    if income in range(1500000,10000000):
        taxable_income = income - 1500000
        tax_amt = 30/100*taxable_income + 187500
        
   
        
    print("The Taxable part of the income is: {}".format(taxable_income))
    print('\n')
    print("The Tax to be paid is: {}".format(tax_amt))
