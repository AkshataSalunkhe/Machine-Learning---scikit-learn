# Machine-Learning-scikit-learn
Practice concepts using scikit learn

1. Linear Models
      
      1.1 OLS - Ordinary Least Squared
         
      1.2 Non negative Linear model
         
      1.3 Ridge regression and classifier


WITH combined_inventory AS (
    SELECT *, 'inventory_part1' as partition FROM inventory_part1
    UNION ALL
    SELECT *, 'inventory_part2' as partition FROM inventory_part2
)
SELECT * FROM combined_inventory WHERE category = 'Dresses';
