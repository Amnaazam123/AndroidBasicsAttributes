# AndroidBasicsAttributes
This application includes understanding of guidline, barrier, visibility and chains concepts.
# Guidline
A guidLine - visual guide which will not be set at run time, used to allign vertically and horizontally in constraint layout.

(The same line of code for margin is written in xml file for three widgets)

![image](https://user-images.githubusercontent.com/71166016/166986465-c4062e12-dde2-44e1-8222-75532359c5c1.png)

# Good Approach
 - Instead of applying margin on all views explicitly, this work can be done through guidline.
 - Remove all the constraints, Add guidline, fix it at one position and add constraints of those views with guidline to which you want to align. 
 - This will create one component in xml file with guidline attribute, and its guidline id will be assigned to all those views which are aligned with this guidline.
 
![image](https://user-images.githubusercontent.com/71166016/166987378-0bcff389-9a9d-47c6-817d-9d25f140bbb2.png)

# Barriers
# - WHY barriers??
When we increased the text in first text view it was overwritten with second text view that was issue with fixed guidline because second text view was constrained with button not first view text.

![image](https://user-images.githubusercontent.com/71166016/166993954-dbfd65eb-ca0d-4f1d-8b99-f4e7f096edab.png)
![image](https://user-images.githubusercontent.com/71166016/166994208-20f402a1-0d58-4662-80d3-93c1782e155e.png)

 - When you assign direction to your barrier, it will position at that side with that view which is expanded most. Make sure to contraint left, your second text view, with barrier now(through xml file). 

![image](https://user-images.githubusercontent.com/71166016/167002041-df08b02b-5ab1-4e80-a2ea-720310519dd7.png)
![image](https://user-images.githubusercontent.com/71166016/167004347-f3748c31-ff33-41d8-b137-1dc8bfa0cc82.png)

# visibility
1 - visible(by default)

2 - invisible(do not leave space)

3 - gone(leave space but maintains constraints)

![image](https://user-images.githubusercontent.com/71166016/167005968-6f0dfdae-b126-4124-a95d-d7c1f9987f9f.png)
![image](https://user-images.githubusercontent.com/71166016/167006035-bc9dad90-84ec-4e47-87df-587b568b54d9.png)
![image](https://user-images.githubusercontent.com/71166016/167006129-fb8662f5-9c76-4446-841b-4319189f3796.png)

# chain

![image](https://user-images.githubusercontent.com/71166016/167006564-7f7f2e09-9cdf-4e6d-a60b-243d1730b22c.png)
![image](https://user-images.githubusercontent.com/71166016/167006627-7a08bbfb-32ee-4f1e-8b31-5fd28b09804d.png)
![image](https://user-images.githubusercontent.com/71166016/167008798-8524ca5b-142a-4324-90b7-5a4074120b4d.png)










