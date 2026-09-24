# loops_and_condition
This repository contains simple codes about loops and conditions
#Trees 

trees = 91

while trees <= 100:
    trees += 3
    print (f"Trees planted: {trees}")

#Cows counting

cows = [45,32,75,28,90]

high_count = []
low_count = []

for cow in cows:
    if cow >= 40:
        high_count.append(cow)
    else:
        low_count.append(cow)

print(f"High count: {len(high_count)}")
print(f"Low count: {len(low_count)}")

#Stock check

stock = [120,85,97,143,213,76,65,98,110,134,150,200,175,190,220,250,300,400,500,600,700]

high_stock = []
low_stock = []

for items in stock:
    if items>=150:
        high_stock.append(items)
    else:
        low_stock.append(items)

print(f"High stock items: {len(high_stock)}")
print(f"Low stock items: {len(low_stock)}")

#Daily sales in dollars over two weeks

daily_sales = [1200,1500,1800,2000,2200,2500,3000,3500,4000,4500,5000,5500,6000,6500]

high_sales = []
low_sales = []

for sales in daily_sales:
    if sales >= 3000:
        high_sales.append(sales)
    else:
        low_sales.append(sales)
        
print(f"High sales days: {len(high_sales)}")
print(f"Low sales days: {len(low_sales)}")
