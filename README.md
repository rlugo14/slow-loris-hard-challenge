# Slow Loris (Hard) Challenge

In this scenario you have a list of calibrated masses. For every weight (of the Slow Loris) which is given to your function you should return a List of ArrayLists with the masses you need for weighing the Slow Loris. Note that you can use every single mass only once! Also note that your Slow Loris sits on the left plate.

## Objective

Your task is to write an algorithm which receive the weigh of the animal and return the different masses (gram) which are used in an List of ArrayLists.

### **Szenario 1:** Our tiny Slow Loris got heavy!

> Given is a `List<Integer>` which includes all calibrated masses of the balance: allMasses = `[1, 3, 9, 27, 81, 243]`

> Your Slow Loris weighs 346 grams.

> Your function should return an `List<ArrayList<Integer>>` with two lists (the first for the left plate, the second for the right plate): `[[leftPlate], [rightPlate]]`.

> Your list should look like this: result = `[[9], [1, 3, 27, 81, 243]]`

![](https://s3.eu-central-1.amazonaws.com/task-static-files/weigh-the-slow-loris-hardmode/scale.png)

> Your algorithm should work with lighter and heavier slow loris as well.






