MIDTERM LAB TASK 2

<img width="744" height="780" alt="image" src="https://github.com/user-attachments/assets/7ecd8b12-e532-4ebd-a904-32db9029740a" />

Source Code:
                        
            product_name = str(input("Enter Product Name:"))
            category = str(input("Enter Category:"))
            quality = float(input("Enter Quality Rating:"))
            price = float(input("Enter Price Rating:"))
            service = float(input("Enter Service Rating:"))            
            
            def calculate_average_rating(quality,price,service):
            total = quality + price + service
            avg = total / 3
            return avg
            
            def analyze_product():
            print("Product Name: %s " %product_name )
            print("Category: %s" % category )
            print("Quality Rating: %.2f" % quality)
            print("Price Rating: %.2f "% price)
            print("Service Rating: %.2f" % service)
            print("Overall Average Rating: %.2f" % calculate_average_rating(quality,
            price, service))
            analyze_product()                       

Sample Output 1:

<img width="444" height="260" alt="image" src="https://github.com/user-attachments/assets/ad5e082a-e9f4-4279-b3f1-a7b0791ee8cc" />

Sample Output 2:

<img width="363" height="250" alt="image" src="https://github.com/user-attachments/assets/7588fd7b-9116-431f-91f2-2236d1409e0f" />



