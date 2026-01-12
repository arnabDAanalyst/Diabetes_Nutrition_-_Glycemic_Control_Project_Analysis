# Diabetes Nutrition & Glycemic Control Project Analysis

![bg](https://github.com/user-attachments/assets/b6e6bcc2-ddf3-4d31-948d-3b78f33689b2)

# 📊 Dataset Structure

Total Records (Rows): 224

Total Attributes (Columns): 12

Data Type: Structured tabular data

Granularity: One row represents one meal consumed at a specific time

 Domain: Healthcare, Nutrition, Lifestyle Analytics
🧾 Detailed Column Description
1. Day_No

 Represents the day sequence of the meal plan (Day-1, Day-2, etc.)

 Helps in daily aggregation of calories and nutrients

 Useful for trend analysis and daily diet comparison

2. Group_Status

 Indicates the health condition combined with physical activity

 Categories include:
o Diabetic_Active
o Diabetic_NotActive
o NonDiabetic_Active
o NonDiabetic_NotActive

 This is the most important segmentation column

 Used to compare:
o Diabetic vs Non-Diabetic
o Active vs Sedentary lifestyle

3. Veg_NonVeg

 Specifies whether the meal is Vegetarian or Non-Vegetarian

 Helps analyze:
o Nutritional differences
o Glycemic impact of diet type

 Useful for diet planning and recommendations

4. Meal

 Identifies the meal category:
o Breakfast
o Lunch
o Snack
o Dinner

 Enables meal-wise nutritional analysis

 Helps detect high-risk meals (e.g., high-carb dinner)

5. Time

 Records the meal consumption time

 Supports:
o Meal timing behavior analysis
o Lifestyle routine insights

 Important for understanding metabolic impact

6. Dish

 Name of the specific food item

 Allows:
o Dish-level comparison
o Identification of diabetic-friendly meals

 Useful for recommendation systems

7. Calories

 Total energy intake per meal (in kcal)

 Key metric for:
o Weight control
o Energy balance analysis

 Can be aggregated to calculate daily calorie intake

8. Protein (g)

 Protein content of the meal

 Important for:
o Muscle maintenance
o Blood sugar stabilization

 Often compared across active vs inactive groups

9. Carbs (g)

 Total carbohydrate content

 Critical column for diabetes analysis

 High carbs usually correlate with:
o Higher blood glucose
o Higher glycemic load

10. Fat (g)

 Total fat content

 Helps evaluate:
o Diet quality
o Heart-health impact

 Often analyzed with calories

11. Fiber (g)

 Dietary fiber intake

 High fiber meals:
o Slow glucose absorption
o Improve digestion

 Strongly linked to lower glycemic index

12. Glycemic Index

 Measures how quickly food raises blood sugar

 Scale:
o Low GI → Diabetes friendly
o High GI → Blood sugar spike


# Business Analysis Questions

1. Average Glycemia level by food meal.

2. Find out daily calories (Breakfast, Lunch, Dinner & Snacks)

3. How much average daily nutrients intake.

4. Find out Group-wise meal average Glycemic index.

5. Find out Total Veg and Non-veg calories.

![Diabetes Nutrition   Glycemic Control Project Analysis Dashboard2](https://github.com/user-attachments/assets/7a56e93e-eddb-463c-bcc1-18e23f5e0980)


